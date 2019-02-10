# Eye2C-Board

## What is the Eye2C board?

The Eye2C board is for the raspberry pi and will provide you with 3 i2c headers and 4 HC-SR04 ultrasonic sensors. It's primary use will be in robotics projects where all round 'vision' is required along with multiple i2c devices (like an adafruit 16 channel servo board, a real time clock, and a simple display). While one of the i2c slots is designed for a tiny i2c oled screen to be added to the board, you can use it as a normal i2c if preferred.

## Where can I get it?

At the moment, this board is in development. You send this board to your preferred supplier for manufacture or visit https://aisler.net/p/ZISHMVAR where Aisler already have the board design and will make you 3 for under €20 euros. All I ask is that you leave the Eye2C name, url and QR code on the board and share any improvements you make back here. There's obviously a disclaimer about the quality of the boards at this time - don't order unless you're willing to accept that the boards might not work.

## Where's the code?

Once I get the initial boards back from manufacture, I'll solder it up and write some code.

GPIO Pins for the HC-SR04's

| Physical Pin | GPIO Number | Sensor	| Function |
|:------------:|-------------|:------:|----------|
| 11 | | HC-SR04 1 | Trig |
| 13 | | HC-SR04 1 | Echo |
| 15 | | HC-SR04 2 | Trig |
| 29 | | HC-SR04 2 | Echo |
| 31 | | HC-SR04 3 | Trig |
| 33 | | HC-SR04 3 | Echo |
| 35 | | HC-SR04 4 | Trig |
| 37 | | HC-SR04 4 | Echo |
