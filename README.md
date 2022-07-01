# LCD_SharpBoosterPack_SPI  Library

[![Arduino Compile Sketches](https://github.com/Andy4495/LCD_SharpBoosterPack_SPI/actions/workflows/arduino-compile-sketches.yml/badge.svg)](https://github.com/Andy4495/LCD_SharpBoosterPack_SPI/actions/workflows/arduino-compile-sketches.yml)
[![Check Markdown Links](https://github.com/Andy4495/LCD_SharpBoosterPack_SPI/actions/workflows/CheckMarkdownLinks.yml/badge.svg)](https://github.com/Andy4495/LCD_SharpBoosterPack_SPI/actions/workflows/CheckMarkdownLinks.yml)

This is a copy of the [LCD_SharpBoosterPack_SPI library][4] that is included with the [Energia application][1].

Texas Instruments MSP430 and Tiva microcontrollers can be compiled using the Arduino IDE/CLI by installing the relevant [platform cores][6] through the Boards Manager. However, the LCD_SharpBoosterPack_SPI library is included in the Energia application itself, and not the specific platform cores. This means that if you install the MSP430 or Tiva core, you don't end up getting the LCD_SharpBoosterPack_SPI library. So a sketch that used that library and compiled fine on Energia would not compile on Arduino without some additional steps.

So I am publishing this library separately so that it can be easily installed as a library for the Arduino IDE or CLI. This also makes it available for use in GitHub workflow actions.

## Usage

See the sketches in the `examples` folder.

## License

The source code in this library is licensed under the terms of the Creative Commons [Attribution-NonCommercial-ShareAlike][100] license, aslo referred to as [CC BY-NC-SA][102].

[1]: https://energia.nu
[2]: https://energia.nu/guide/libraries/
[3]: https://github.com/robertinant/EnergiaNG
[4]: https://github.com/robertinant/EnergiaNG/tree/master/libraries/LCD_SharpBoosterPack_SPI
[6]: https://arduino.github.io/arduino-cli/0.21/platform-specification/
[100]: https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode
[102]: https://creativecommons.org/licenses/by-nc-sa/3.0/
[200]: https://github.com/Andy4495/LCD_SharpBoosterPack_SPI

[//]: # (This is a way to hack a comment in Markdown. This will not be displayed when rendered.)
