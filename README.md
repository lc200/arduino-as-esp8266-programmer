# arduino-as-esp8266-programmer
This short sketch allows an Arduino to become a programmer for a ESP8266 (such as AI-Thinker) over serial where the ESP8266 doesn't come on a development board with USB/Serial.

The bare bones ESP8266 needs to be wired up using the following connections, this will allow the Arduino to pull pins high/low as necessary to automatically start programming mode on the AI-Thinker.  It will then be possible to flash an Arduino sketch to the ESP8266 with minimal trouble.





