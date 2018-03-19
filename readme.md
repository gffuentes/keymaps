# Custom Keymaps For Clueboard (and default)
For use with [QMK firmware](https://docs.qmk.fm). Also where default clueboard layout in this repo comes from.

## Make & Flash
1. Enter programming mode: Fn + S + R
2. Confirm programming mode: `lsusb` (Linux) or `system_profiler SPUSBDataType` (Mac) 
3. `cd ~/.../qmk_firmware`
4. `make clueboard/66/rev3:gaberson:dfu`
