# Ragnarok Storage Bot v72.80

- Replaced only the Blue Herb drag action in the purchase flow with the tested SendInput 4-step + `MOUSEEVENTF_MOVE_NOCOALESCE` method.
- Replaced only the Blue Herb withdrawal drag from Kafra storage to Inventory with the same method.
- Uses a 20 ms source hold, four movement steps, and an 80 ms destination settle before release.
- Keeps all existing clicks, quantity entry, confirmation buttons, visual verification, fallback clicks, and retry behavior unchanged.
- Safely releases mouse buttons and continues to the existing visual verification when an input worker reports a failure.
- The Inventory-to-Kafra Blue Herb deposit action remains Alt+right-click because that flow does not use dragging.

SHA256: `18FFADDB43FC70219E7720776DEFC7CF65E39646BFBD532C897F59ECAF532EC7`
