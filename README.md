# Space-Invaders
Space invaders is a retro arcade game. This time, implemented on the ARM Cortex M4 microcontroller.

### Required Hardware I/O connections-
| Connection	| uC pins |
|-------------|---------|
| Slide pot pin 1 | Ground |
| Slide pot pin 2 | PE2/AIN1 |
| Slide pot pin 3 | +3.3V |
| Fire button | PE0 |
| Nokia 5110 (LCD-10168) |  |
| VCC | +3.3V |
| GND | Ground |
| SCE(SSI0Fss) | PA3 |
| RST(Reset) | PA7 |
| D/C(Data/Command) | PA6 |
| DN(SSI0Tx) | PA5 |
| SCLK(SSI0Clk) | PA2 |
| LED | not connected |


### How to Run

1. Connect pins as mentioned above.
2. Open minorproject.uvproj with Keil UVision IDE.
3. Connect the microcontroller 'Launch Pad' to the computer via USB.
4. Load the program into the microcontroller.


### Built With
Built on the ARM Cortex M4 microcontroller, TM4C123GH6PM, with the Texas Instruments Tiva C series TM4C123G Launch Pad. 

Keil uVision4 used as the IDE.


