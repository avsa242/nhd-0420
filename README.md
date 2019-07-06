# us2066-spin
---------------

This is a P8X32A/Propeller driver object for US2066-based alphanumeric OLED displays, such as:
[Newhaven Display's NHD-0420-CW-Ax3 series](http://www.newhavendisplay.com/nhd0420cway3-p-7829.html)

## Salient Features

* I2C connection up to 400kHz
* API compatible with display.lcd.serial
* Set contrast level
* Set cursor attributes: blinking, inverted, shape
* Set text attributes: double-height. 5 and 6-pixel width text
* Inverted/normal display
* Display mirroring (horizontal/vertical/both)

## Requirements

* 1 extra core/cog for the PASM I2C driver

## Limitations

* Support for different display dimensions (e.g., 2x16, 4x20) is limited
* No scrolling support (chipset has horizontal scrolling support)
* No support for custom characters

## TODO

- [ ] Review API to see if it makes sense to make some methods PRI
- [ ] Customer character sets
- [ ] Scrolling support
- [ ] SPI variant
