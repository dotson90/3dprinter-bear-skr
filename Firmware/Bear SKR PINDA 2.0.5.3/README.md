# Bear SKR 2.0.5.3

ใช้สำหรับ P.I.N.D.A เท่านั้น

มีการปรับปรุง และแก้ไขปัญหาต่าง ๆ ดังนี้

### New Features

* Add QSPI EEPROM for SAMD51.
* Case Light brightness stored in EEPROM.

### Issues Patched

* Fix Max7219 delay timing.
* Remove extra call to unskew.
* Formbot T-Rex 2+ default LCD timings.
* Fix M0 unused var warning.
* Fix stepper PWM menu.
* Float pins that can't pull down.
* Fix bad final M2/M3 Arc segment.

### Optimized / Improved

* Simplified SD completion.

### Configuration

* Allow PID_DEBUG to be turned on/off.

### Boards / Pins

* Funmat HT v4.0 board support.
* Fix up Trigorilla 1.4 pins.
* Fix FYSETC STM32 flash usage.
* Fix PINS_DEBUGGING build on STM32F1.

### Hosts and UI

* Update Russian and Italian languages.
* Fix SD finished ExtUI / host action.
* Limited backlash editing with Core kinematics.
* Fix / improve FTDI EVE Touch UI.

### เปิดใช้ Feature ใหม่

* เปิดใช้งานตั้งฐานพิมพ์อัตโนมัติแบบ UBL
