# Space-Invaders

Space invaders is one of the most famous arcade game, originally released in 1978. Space Invaders is a shooting game, with the objective being to survive the waves of alien ships.

There are three rows of alien ships at the top of the screen. The player's ship is at the bottom, along with three bunkers for the player to hide behind, between the player and the alien ships.
The player has to destroy the alien ships while avoiding their fire.

The player is controlled using a slider, which moves the ship horizontally across the screen. The player fires by pressing the button.

A Nokia 5110 screen is used as the display, along with a sliding resistor to control the ship and a button to fire.


### How to Run

1. Connect pins to microcontroller according to the table below.
2. Open 'minorproject.uvproj' with Keil UVision IDE.
3. Compile and load the program into the microcontroller by connecting the 'Launch Pad' to the computer via USB.
4. Disconnect the USB cable and attach it to a power supply(eg. back to the USB port itself), which starts the program on the microcontroller.


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


### Built With
Built on the ARM Cortex M4 microcontroller, TM4C123GH6PM, with the Texas Instruments Tiva C series TM4C123G Launch Pad. 

Keil uVision4 used as the IDE.


