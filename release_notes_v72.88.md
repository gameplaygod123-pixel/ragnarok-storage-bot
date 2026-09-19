# Ragnarok Storage Bot v72.88

- Removed the immediate `arrow_slot1_17` scan after page 3 deposits.
- The storage flow now checks and clears `arrow_slot1_17` once, at the final pre-close stage.
- `CloseKafra` skips its internal duplicate `arrow_slot1_17` scan when the storage flow has already completed that final check.
- Other flows retain the original pre-close safety check, and popup 19/top-popup checks remain unchanged.

SHA256: `A6CDC5FD1FAF7F3924343D88EC94A41FA432FF4DF032665262E87E81205E6E8D`
