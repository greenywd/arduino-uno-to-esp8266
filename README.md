# arduino-uno-to-esp8266
How to configure an Arduino Uno to program an esp8266-01

![Breadboard](https://github.com/greenywd/arduino-uno-to-esp8266/blob/master/Configuration.png)

| Arduino Uno   | esp8266       |
| ------------- |---------------|
| 3.3v          | VCC, CH_PD    |
| GND           | GND, GPIO_0   |
| TX            | TXD           |
| RX            | RXD           |

And Arduino Uno GND to RESET as seen above. Install the esp8266 boards from inside the Arduino IDE, select "Generic ESP8266 Module" and upload your code! Yes, TX > TXD and RX > RXD is correct - blame the manufactuer I guess ¯\_(ツ)_/¯
