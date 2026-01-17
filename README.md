This repository does not provide ready-to-use firmware intended for illegal interference with wireless communications.

License: Apache License 2.0

T-Display-Expansion-Board
OVERVIEW
Hi, I'd like to share my new project, the T-Display Expansion Board, which aims to expand your T-Display S3 with 7 additional modules.

The project was created primarily for educational, research, and hardware experimentation purposes. It focuses on expanding the s3 with seven additional modules that will enhance its usability.

IMPORTANT: This project is intended for educational and experimental purposes only. Using the module extension for card theft, radio signal jamming, and key duplication is illegal in most countries. The author is not responsible for any misuse of this project.

HARDWARE COMPONENTS
t-display s3
rfid PN532
cc1101
5 ir tx
1 ir rx
sd card module
boost conventer 3.7-5 volt
batery 1000 mAh 3.7 volt
2 pcb 40/70 mm
1 swicht
1 charging module usb c
tranzystor BC547
PIN CONNECTIONS
***rfid module
***pins
gnd|gnd vcc|3.3 sda|44 scl|43

***sd card
***pins
gnd|gnd 3v3|3v3 miso|13 mois|11 cs|1 clk|12

**cc1101
**pins
gnd|gnd 3.3|3.3 sck|12 miso|13 mois|11 cs|2 io0|21

**charging module - boost conventer
**pins
out- | - -> out+ | + ->

**boost conventer - t-display
**pins
| + - | -
** ir tx - tranzystor BC547 (from the smooth side)
** pins
left | gnd middle | g 17 right | - (on ir diod) + (on ir diod) | 3.3

** ir rx (from the smooth side)
**pins
left | 3.3 middle | gnd right | g 18

**PLANNED FEATURES **
add external antena mod
add e01c
add ir tx 3 w
fm si4713 module
lora
DISCLAIMER
This repository is provided for educational and research purposes only. Any functionality that may interfere with wireless communication must be used only in controlled environments and in accordance with local laws.

LICENSE
MIT License Feel free to study, modify, and improve this project responsibly.

AUTHORSHIP AND REDISTRIBUTION
This design may be used and modified.

Crediting this design or presenting it as an original work created by another person is prohibited.

Rebranding, removing author information, or impersonating the author is strictly prohibited.
