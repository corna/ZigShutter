# ZigShutter bootloader

This platform uses the [Adafruit nRF52 Bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader/)
as bootloader.

This folder contains the files needed to build the bootloader for this
platform. To do so, clone the [Adafruit nRF52 Bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader/)
and copy the `ZigShutter` folder into the bootloader's `src/boards` one, then
follow the build and flash instructions specifying `BOARD=ZigShutter`.
