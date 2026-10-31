# Ship Radar


Descended from MatixYO's [ESP32 Plane Radar](https://github.com/MatixYo/ESP32-Plane-Radar) project, adapted from ADS-B aircraft tracking to AIS ship tracking with [AISStream](https://aisstream.io/). using https://github.com/HenrysCat/ESP32-Ship-Radar

The hardware has been changed to run the henryscat software to run on the basic plane radar hardware. (I used AI to help me reprogramme the hardware pins)

To flash the files you need to flash the files below I used online esptool to flash
0x0000     bootloader.bin
0x8000     partitions.bin
0x10000    firmware.bin

This is my first attempt at using git hub so I hope I have not done anything I should not. 
to set up once the screen is on follow the henrys cat set up for api keys etc thanks
