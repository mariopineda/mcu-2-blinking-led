# mcu-2-blinking-led
Microcontroller Unit Assignment 2: Single blinking LED

In this assignment you will program you MCU to blink the "onboard LED".

1. You will be using the Arduino IDE for programing your MCU. If the SArduino IDE is not yet installed on your Raspberry Pi install it by running the following command in the terminal: ```sudo apt-get install arduino```. Note that you need to have administrative priviliges to run the install (if you get a message saying something along the line of you not being in the sudoers file, talk to your teacher).
2. Connect the FTDI connector to your bread board (see the [mcu-build](https://github.com/mariopineda/mcu-build) assignment for instructions for how to do this).
3. On your Raspberry Pi launch the Arduino IDE (under Electronics in the Raspberry menu). 
4. In the Arduino IDE:
  * Tools > Board and select Arduino Uno
  * Tools > Serial Port and select ```/dev/ttyUSB0```
  * Tools > Programmer and select AVRISP mkII
5. Open up the blink sketch (File > Examples > 01. Basics > Blink)
6. Modify the blink timing to 100 milliseconds on and 100 milliseconds off. Compile and upload the sketch to your MCU. 
