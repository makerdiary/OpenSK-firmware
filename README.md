# OpenSK Firmware

[![Current Version](https://img.shields.io/github/tag/makerdiary/OpenSK-firmware.svg)](https://github.com/makerdiary/OpenSK-firmware/tags)
[![Build Firmware](https://github.com/makerdiary/OpenSK-firmware/actions/workflows/firmware.yml/badge.svg?branch=main)](https://github.com/makerdiary/OpenSK-firmware/actions/workflows/firmware.yml?query=branch%3Amain)

This repository is used to release the latest [OpenSK](https://github.com/google/OpenSK/tree/develop) firmware for Makerdiary's nRF52840-based boards with UF2 Bootloader.

## Supported Hardware

* [nRF52840 MDK USB Dongle PCBA](https://makerdiary.com/products/nrf52840-mdk-usb-dongle)
* [nRF52840 MDK USB Dongle w/Case](https://makerdiary.com/products/nrf52840-mdk-usb-dongle-w-case)

## Releases

The latest OpenSK firmware can be downloaded from [here](https://github.com/makerdiary/OpenSK-firmware/releases).

## Getting Started

Download the [latest firmware](https://github.com/makerdiary/OpenSK-firmware/releases) and complete the following steps to test the firmware:

1. Push and hold the button and plug your dongle into the USB port of your computer. Release the button after your dongle is connected. The RGB LED turns green.
2. It will mount as a Mass Storage Device called __UF2BOOT__.
3. Drag and drop `opensk-nrf52840_mdk_usb_dongle-<version>.uf2` onto the __UF2BOOT__ volume. The RGB LED blinks red fast during flashing.
4. Re-plug the dongle and the OpenSK device will start running.
5. Visit https://webauthn.io/ to test the firmware.

## Community Support

Community support is provided via [GitHub Discussions](https://github.com/makerdiary/OpenSK-firmware/discussions).

## License
Copyright (c) 2016-2023 Makerdiary. See [LICENSE](./LICENSE) for further details.
