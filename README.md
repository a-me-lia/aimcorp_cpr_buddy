## Production Instructions

This files in the /production folder are nicely packaged for ordering at JLCPCB or most other PCB brokering services.

This board is designed to be 2-layer. The quoting software should automatically select the minimum tolerances as well. 

After uploading BOM, if you need to select component because a component did not autopopulate, open the BOM file and look for the corresponding designator. Put the LCSC number in LCSC search and find an identical component in the JLC Parts search feature. You can use LCSC C-numbers in JLCPCB as well.

## Programming instructions

This board is designed to work out of the box with a standard 6-pin FTDI breakout. The programming port is not populated with the pin header so you can insert the FTDI board right in. 

Please refer to the ESP-12F datasheet for information regarding bootloader mode strapping. All physical interfaces for pin strapping is provided via a 4-pin interface on the board.#   a i m c o r p _ c p r _ b u d d y  
 