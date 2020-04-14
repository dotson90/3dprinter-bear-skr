# Bear SKR TFT35 V3 xx.26

ใช้สำหรับ หน้าจอ BigTreeTech TFT35 V.3 เท่านั้น

มีการปรับปรุง และแก้ไขปัญหาต่าง ๆ ดังนี้

### เพิ่มเมนู

* เปลี่ยนหัวพิมพ์
* Calibration อัตโนมัติ
* Calibration สำหรับพิมพ์เส้น PLA
* Calibration สำหรับเส้น PETG
* ทำความสะอาดหัวพิมพ์ด้วยวิธีการ Cold Pull อัตโนมัติ
* เปิดให้ Feed เส้นในขนณะที่หัวพิมพ์เย็นได้
* ยกเลิกการ Feed เส้นในขฯะที่หัวพิมพ์เย็น
* Bed Level แบบ UBL อัตโนมัติ พร้อมทั้ง Save เข้า EEPROM Slot 1
* Bed Level แบบ UBL อัตโนมัติ พร้อมทั้ง Save เข้า EEPROM Slot 2
* Bed Level แบบ UBL อัตโนมัติ พร้อมทั้ง Save เข้า EEPROM Slot 3
* ตั้งระยะหัวพิมพ์แบบ UBL ขั้นตอนที่ 1
* ตั้งระยะหัวพิมพ์แบบ UBL ขั้นตอนที่ 2 พร้อมทั้ง Save เข้า EEPROM
* ทำการพิมพ์เพื่อทดสอบ Bed Level
* Adjust Point Near
* ล้าง EEPROM ไปเป็นค่าตั้งต้น

### New Features

* Add LCD backlight control, auto sleep function (Settings->Feature->LCD Brightness)
* Add more Printer setting parameters (Steps/mm, TMC driver current, Feedrate, Acceleration, etc...)
* Add new language(Polish, Slovak, Dutch, Hungarian), up to 15 languages are now supported
* Add support "M300" gcode for TFT buzzer
* Add the TFT with encoder can control the value of menu by encoder
* Add long file name display of onBoardSD(required LONG_FILENAME_HOST_SUPPORT in Marlin)

### Improve

* Improve print menu layout
* Improve Smart Filament Sensor(SFS), (note: required M114_DETAIL and disable LIN_ADVANCE in Marlin, because now LIN_ADVANCE have bugs in Marlin, will be fixed later)
* Improve the tips of "M117" and "echo:" from Marlin
* Improve power loss recovery(PLR), The printing state is saved per layer to reduce the wear of SD card(only support print from TFTSD card now).
* Improve model preview(only support print from TFTSD card now)
* Add more baudrate options on TFT screen

### Bugfix

* Fix error PS_ON_PIN from “PA12” to "PC12" in TFT35_V3.0
* Fix "M104","M109", 'R'/'B'/'F' parameters bug.
