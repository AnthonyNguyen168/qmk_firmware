# Canary60RGB

A hotswap 60% RGB keyboard.

* Keyboard Maintainer: [tuananhnguyen204](https://github.com/AnthonyNguyen168) (tuananhnguyen204@gmail.com)
* Hardware Supported: CanaryTeam Canary60RGB v1
* Hardware Availability: [CanaryTeam](https://www.facebook.com/CanaryTeam/), [Shopee](https://shopee.vn/search?keyword=canary60rgb)

## Bootloader mode

Enter the bootloader in 3 ways:

* Bootmagic reset: Hold down the left top key then plug in the USB cable.
* Physical reset button: Double tap the reset button.
* Keycode in layout: Press the key mapped to QK_BOOT if it is available.

## Making firmware

Make example for this keyboard (after setting up your build environment):
    make canary/canary60rgb/v1:default # AVR (ATmega32U4)
	
See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
