## **Binary Counter and Seven-segment Display**

Laboratory Objective:
* To perform I/O operation on the AVR port of the ATmega 328p microcontroller.
Materials:
* Microchip Studio (Previously ATMEL Studio)
* Arduino Uno Kit
* LEDs
* Resistors
* Push Buttons
A. Seven-segment Display Background

The objective of this laboratory activity is to design and implement a seven-segment display using
Arduino Uno microcontroller and assembly program, as shown in Figure 1. Each of the seven
segments is labeled “a” through “g”. The numbers “0” through “F” light up the segments shown in
Figure 2. For example, the number 0 lights up all but the middle segment, segment g.

![Screenshot 2023-10-03 100739](https://github.com/FrancesNicole/Embedded-System-Programming/assets/116133070/91881f47-942d-46d2-ac09-820cbe4c74ea)

You will build a seven-segment display using LEDs and resistors, shown in Figure 3. The
circuit has four input bits, using push buttons (e.g., PB 0 , PB 1 , PB 2 , and PB 3 ) (representing a
hexadecimal number between 0 and F), and produces seven output bits, S a:g , that drive the seven
segments to display the number. A segment of the display turns on when it is LOW or 0. Such an
output is called a low-asserted output or active low output. Another version of this is a segment of the
display turns on when it is HIGH or 1. Such an output is called a high-asserted output or active high

![Screenshot 2023-10-03 101134](https://github.com/FrancesNicole/Embedded-System-Programming/assets/116133070/c8cb8550-d9d3-4636-ae3a-ae79eddc7d13)

Connect all four push buttons to the Arduino Uno pins on a breadboard using the pull-down
configuration previously discussed in our lecture schedule. Then, connect the LEDs, forming a seven-
segment display portrayed and discussed in the previous section.
In this exercise, you should work solo. You are required to write the function BinaryCounter_SSD
in the code skeleton provided, using the PINC for digital input, PORTB and PORTD for digital
output, and Boolean algebra.
