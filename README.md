# Arduino-I2C-Expander

Use an Arduino or any ATMega as digital/analog IO expander, DAC, PWM controller, EEPROM, external RAM etc... via I2C

If you ran out of IO pins with your ESP8266 or any other MCU, adding an Arduino Nano can be an alternative to specialized chips. Using an ATMega88 instead of the 328P can be a cheap and powerful solution compared to other options PCF8574, CD74HC4067, ....

## Functionality

- up to 6 8bit DACs, or 3 with 16bit
- up to 6 PWM channels (4x31.2/2x62.5kHz)
- 6 analog and digital inputs/outputs
- pin 2/3 with external interrupts
- serial EEPROM
- external RAM

## Supported functions

- digitalRead
- digitalWrite
- analogRead
- analogWrite
- pinMode
- attachInterrupt
- detachInterrupt
- SFR read/write

## TODO

- EEPROM Read/Write
- malloc/free/memcpy
