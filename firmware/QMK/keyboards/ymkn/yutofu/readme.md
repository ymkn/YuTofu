# ymkn/yutofu

YuTofu is an unofficial compatible PCB for the well-known custom keyboard [Tofu60 2.0](https://kbdfans.com/products/tofu60-2-0).

* Keyboard Maintainer: [ymkn](https://github.com/ymkn)

Make example for this keyboard (after setting up your build environment):

    make ymkn/yutofu:vial

Flashing example for this keyboard:

1. Enter the bootloader.
2. Simply copy ymkn_yutofu_vial.uf2 to RPI_RP2 drive.

This keyboard supports [Vial](https://get.vial.today/) configurator.

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
