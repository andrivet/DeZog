# DeZog with ZX81 support

This is backporting of [ZX81 Debugger](https://github.com/andrivet/ZX81-Debugger) into the latest version of [DeZog](https://github.com/maziac/DeZog).

To use it:

* download the latest VSIX file [Release](https://github.com/andrivet/DeZog/releases),
* click on the Extensions icon the left,
* click in the three dots (...) on the top of the Extensions panel and choose `Install from VSIX`,
* choose the VSIX file previously downloaded,
* This will install `DeZog with ZX81`.

Note: If my [PR](https://github.com/maziac/DeZog/pull/130) is merged into the upstreeam DeZog, I will remove this branch and the VSIX. This is a temporary solution.

## Features

* Support of the ZX81 display (including in 1K mode)
* Basic support of ZX81 keyboard (the keyboard -- i.e. your keyboard -- works but the simulator does not give feedback yet when pressing a key and it is not possible to press a key on the image of the keyboard)
* Support various memory models (ZX81 with 1K, Timex Sinclair TS1000 with 2K, ZX81 with 16k, 32k, 48k or 58k RAM packs).
* If 'execAddress` is not specified, the program is assumed to start at 16514.

## Known limitations

* FRAMES and LASTK system variables are not yet updated when the ROM is not called.
* The ZX81 character set is not displayed.
* HiRes is not yet supported.
*The ZX80 is not supported.
