# Ragnarok Storage Bot v72.86

- In the Run All Loop Blue Herb gate, two consecutive missing quantity reads now mean a count of zero.
- A zero count continues directly to the configured Blue Herb withdrawal instead of failing the current game screen.
- The existing weight guard remains active and reserves one unit of free Inventory weight.
- Normal stable-count handling remains unchanged when quantity digits are visible.

SHA256: `15D5B3D079E237E40D650DA4A8B0F5A8F6C6BEFCF0C64F502F9A6322CD1F426B`
