# arduino-as-esp8266-programmer
This short sketch allows an Arduino to become a programmer for a ESP8266 (such as AI-Thinker) over serial where the ESP8266 doesn't come on a development board with USB/Serial.

The bare bones ESP8266 needs to be wired up using the following connections, this will allow the Arduino to pull pins high/low as necessary to automatically start programming mode on the ESP8266.  It will then be possible to flash an Arduino sketch to the ESP8266 with minimal trouble just by selecting the COM port as normal.

This is tested from an Atmel SAMD21 (Arduino Zero or similar) but should work on all similar variants.  Note that using a 5 volt style of Arduino (like an Uno) will damage the ESP8266.

## Connections
The following connections should be made.

RX from the programmer to the TX pin of the ESP8266

TX from the programmer to the RX pin of the ESP8266








