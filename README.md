Brief Description

SegMap Nano is an Arduino Nano-based 7-segment display tester and pinout mapper with an OLED interface.
When probing a segment pin with 5V, the OLED visually highlights the corresponding segment on a digital 7-segment graphic and displays its segment label (A–G or DP) along with the display pin number.

The tool is useful for:

Identifying unknown 7-segment displays
Learning 7-segment layouts
Troubleshooting segment connections
Salvaging and mapping old LED displays

Uses:

Arduino Nano
SSD1306 OLED display
Common cathode 7-segment display
External pulldown resistors for stable detection
Single digit 7 segment tester so when you touch a segment pin with VCC through a wire, the OLED shows which segment (A–G or DP) and which pin (1–10) it is. Good idea for identifying unknown displays. 
Concept 
•	Common cathode (negative) display  
•	Pin 3 and Pin 8 usually go to GND through 330Ω  
•	Each segment pin goes to an Arduino Nano input  
•	When you touch a segment pin with VCC, the Arduino detects HIGH and prints the segment name on the OLED.  
Example Pin Mapping (edit if needed) 
Segment 	Display Pin 	Arduino Pin 
A 	7 	D2 
B 	6 	D3 
C 	4 	D4 
D 	2 	D5 
E 	1 	D6 
F 	9 	D7 
G 	10 	D8 
DP 	5 	D9 
OLED (SSD1306 I2C) 
OLED 	Arduino 
SDA 	A4 
SCL 	A5 
