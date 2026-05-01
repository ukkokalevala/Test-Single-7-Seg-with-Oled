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
