Chipkit OLED (sh1106) library for Adafruit_GFX
==============================================

This is a library for monochrome OLED 128x64 with SH1106 driver.
The OLED has it's own built in DC/DC convertor which we use to provide the OLED drive voltage.

Only 4 SPI + Reset is supported.
	MOSI : Data
	CLK : Clock
	CS : Chip Select
	D/C : Data/Command
	RST : Reset

Built to run on Chipkit and use the DSPI library.

Adapted from the Adafruit SSD1306 driver.
The SSD1306 and SH1106 are very similar but have a few important differences.
Written to be compatible with the Adafruit_GFX library.
