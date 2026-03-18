# The Reek LED Control Contraption
This project is basically a controller which switches between two different oscillations for two LEDs. One switch leads it to being in constant oscillation between the two circuits. The other switch makes the oscillations creepy and kinda random.\
<img width="682" height="597" alt="Screenshot 2026-03-18 200943" src="https://github.com/user-attachments/assets/e472c0e6-3ad5-432b-a997-a610e03c2f35" />
## The circuit!
This circuit consists of 16 resistors of various resistances, 6 transistors and 4 capacitors of various capacitances as the main parts and then the inputs and outputs. A more detailed list is given in the BOM.
The entire circuit is basically just 3 multivibrators working together! The main bistable circuit acts as the switch that transfers current between the two different oscillation "modes". Then the current triggers a transistor which allows the 5V to pass through an astable circuit. There are two astable circuits with different combinations of resistors and capacitors. The outputs of both the astable circuits lead to two LEDs which provide as the output in this circuit!\
![circuit1](https://github.com/user-attachments/assets/03d56ba3-4aa3-45d5-bbd3-c26466e297d3)
## Try it out!
https://is.gd/1EUmVZ
## Schematic
The Schematic was made in KiCad!\
<img width="920" height="564" alt="Screenshot 2026-03-18 222541" src="https://github.com/user-attachments/assets/a839df84-9158-4090-9f74-c25ca1bdd2f1" />
## PCB
I decided to make the PCB the shape of the chrome dino with the LEDs as it's eyes. But the dino only has one eye so I just improvised the other one's position!
<img width="1024" height="852" alt="Screenshot 2026-03-18 200929" src="https://github.com/user-attachments/assets/924c4704-adfd-4ac7-9ac3-608438daacb6" />
<img width="997" height="859" alt="Screenshot 2026-03-18 201047" src="https://github.com/user-attachments/assets/46e9d8d4-8323-4704-a417-08ecd56a2ab3" />

Thanks for reading! -Sashreek :3
