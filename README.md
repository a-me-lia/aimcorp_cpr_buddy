# Production Instructions

The files in the `/production` folder are ready for ordering at JLCPCB or most other PCB brokering services.

- **Board Design**: This board is designed as a 2-layer PCB. The quoting software should automatically select the minimum tolerances needed.
- **BOM Handling**: 
    - After uploading the BOM, if a component did not autopopulate, locate the corresponding designator in the BOM file.
    - Use the LCSC part number from the BOM to search in the JLC Parts library for an identical component.
    - LCSC "C-numbers" can be directly used in JLCPCB for part selection.

# Programming Instructions

This board is compatible with a standard 6-pin FTDI breakout for programming.

- **Programming Port**: The programming port is not populated with a pin header, allowing direct insertion of the FTDI board.
- **Bootloader Mode Strapping**: Refer to the [ESP-12F datasheet](https://www.espressif.com/sites/default/files/documentation/0a-esp8266ex_datasheet_en.pdf) for details on bootloader mode strapping.
    - All physical interfaces for pin strapping are accessible via a 4-pin interface on the board.
