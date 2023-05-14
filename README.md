# ARIES_4-4-4-LED-CUBE
PROJECT IDEA:-
We obtain various decorative and beautiful patterns on a 4*4*4 LED cube. The code for the patterns is written using Arduino
The main purpose that the led cube serves is in the entertainment sector. For all intents and purposes, it is actually a high-tech display. Think of it as a three-dimensional display consisting of 64 pixels (or voxels in this case) which can be used to visualize any sort of animation or graphics. The cube has commercial potential due to its advanced and unparalleled design.
A led cube is like a led screen but it is special as it has 3D.We can think of it as a low resolution display. In normal displays it is normal to stack pixels closer to each other in order for better resolution but the led cube has its limits.
The project is mainly for entertainment purposes, and can be used for decorative purposes in our houses, offices etc. This cube can act as a mood elevator and can divert your mind from stress causing problems for sometime.
![image](https://github.com/Krish-Roorkee/ARIES_4-4-4-LED-CUBE/assets/101397993/e00c6797-2046-4ebb-b36a-f6758e4f090e)

WORKFLOW:-

1) Testing the LEDs and assembling the 1st layer.

2) Assembling includes using cardboard to make a frame of the LED mesh. 

3) Creating four layers and punching LEDs in the punch holes of cardboard.

 ![image](https://github.com/Krish-Roorkee/ARIES_4-4-4-LED-CUBE/assets/101397993/4f3df77f-318d-45c3-a96d-928ffa3d6aaf)
 
4) Stacking the layers and the cardboard is ready.

5) Writing Arduino code for various patterns and testing them virtually on Tinkercad.

6) Designing of PCB and its connections with LED and Arduino.

7) Coding in the arduino can be modified and better patterns can be created. Good mapping of 3D objects can be done.

Shift Register IC 74HC595:-
Sometimes we have a number of modules to connect over our arduino, but Arduino UNO have 14 digital I/O pins, to avoid this problem we can use shift register IC.

Shift register IC is like a 3 input and 8 pin digital output decoder, where we use three pins of arduino for our signal that will be fed to three input lines of IC and from the output of IC we can decode it back into 8 output lines or bits.

![image](https://github.com/kd2056/ARIES_4-4-4-LED-CUBE/assets/128305932/644366c8-7394-4798-bfd3-7b658c20ed8a)

SHIFT REGISTER IC 74HC595 PIN CONFIGURATION:-
15, 1, 2, 3, 4, 5, 6, 7	Output Pins (Q0 to Q7)-	The 74hc595 has 8 output pins.
8	- Ground	Connected to the Ground  of the circuit
9	(Q7') - Serial Output	This pin is used to connect more than one 74hc595 as cascading (Pin 9 is data out and used when we have to connect another shift register, Feed this pin to next Shift register IC, if connected)
10	(MR)- Master Reset	Resets all outputs as low. Must be held high for normal operation
11	(SH_CP)- Clock	This is the clock pin to which the clock signal has to be provided from MCU/MPU
12	(ST_CP)- Latch	The Latch pin is used to update the data to the output pins.
13	(OE)- Output Enable	The Output Enable is used to turn off the outputs. Must be held low for normal operation
14	(DS)- Serial Data	This is the pin to which data is sent, based on which the 8 outputs are controlled
16	Vcc-	This pin powers the IC, typically +5V is used.

TINKERCAD:- Online 3-D Simulator

![WhatsApp Image 2023-05-14 at 00 50 57](https://github.com/Krish-Roorkee/ARIES_4-4-4-LED-CUBE/assets/101397993/4c21363c-e017-41c7-bf3f-e259db978aa3)

1) We made an exact model of the cube along with Arduino and the shift registers for testing our code.
 
2) There were 5 shift registers used. 4 for controlling the 4 levels and 1 for selection of the level.

3) The simulation gave us an idea regarding the resistances to be used and the changes we were supposed to make in the code.

TEAM MEMBERS:-

1) Ankit Yadav
2) Karandeep Singh
3) Krish Shah
4) Sahil Patel

REFERENCES:-

4*4*4 LED CUBE : 5 Steps (with Pictures) – Instructables.

How to Make a 4x4x4 LED Cube Using Arduino | by DiY Projects Lab | Medium







