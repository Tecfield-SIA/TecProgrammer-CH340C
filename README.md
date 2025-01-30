# TecProgrammer-CH340C
Compact USB-C to Serial (UART) adapter with 3.3V/5V logic selection, ideal for microcontroller programming and debugging.

![STM32f103Cxxx DevBoard](https://github.com/Tecfield-SIA/TecProgrammer-CH340C/blob/main/Images/TecProgrammer.gif)

________________________________________

### Overview

TecProgrammer-CH340C V2.0 is a compact and versatile USB-to-Serial (UART) adapter designed for seamless communication between computers and microcontroller-based projects. This board is ideal for reading UART protocols, debugging embedded systems, and programming microcontrollers.

________________________________________

### Features

__Compact Design:__
- Measuring only 38mm × 22mm, making it highly portable.
  
__USB-C Connector:__
- Unlike most similar adapters that use standard USB-A or micro-USB, this board features a USB-C port for a more modern and reliable connection.
  
__Logic Voltage Selector Switch:__
- Effortlessly switch between 3.3V and 5V logic levels for compatibility with a wide range of microcontrollers, including STM32, ESP32, and ATmega.

__Full CH340C Pinout Access:__ 
- All pins of the CH340C chip are exposed, offering maximum flexibility for advanced users.

__TX/RX Activity LEDs:__ 
- Dedicated TX and RX LEDs provide real-time data transmission and reception indicators for better debugging.

__Optimized Serial Header Layout:__
- Bottom Edge: TX, RX, GND, and VCC pins arranged for easy UART connection.
- Top Edge: Additional pins for programming ATmega microcontrollers (e.g., ATmega128).
- Other Pins: Extra CH340C pins exposed for advanced applications.

__Microcontroller Programming Support:__
- Perfect for flashing firmware onto microcontrollers like STM32, ESP32, and ATmega series.

__High Power Output:__
- Features an AMS1117 voltage regulator capable of supplying up to 1A, delivering more power than typical USB-to-serial adapters.

__Noise Reduction Design:__
- The USB-C shield is isolated from the ground via a 0-ohm ferrite bead, reducing external noise.

__Industry-standard capacitor placement:__
- 10µF and 100nF capacitors at USB-C input and regulator input.
- 10µF and 100nF capacitors at regulator output.

__Open-Source Hardware:__
- All design files, schematics, and PCB layouts will be publicly available.

Future Improvements
•	Zener Diode Protection: The next revision will incorporate a 5.6V Zener diode for enhanced input protection.
•	ESP32 Auto-Programming Circuit: While DTR and RTS pins are exposed, the current version does not include the required transistor circuit for automatic ESP32 flashing. A future version will integrate this feature.

Supported Baud Rates
•	The CH340C chip supports baud rates up to 2 Mbps, ensuring high-speed communication.

Licensing
This project will be released under an open-source license. Recommended options:
•	MIT License – Permissive, allowing broad use.
•	GNU GPL – Ensures modifications remain open-source.
•	Apache License – Adds extra patent protection.

Getting Started
1.	Connect the board to your computer via USB-C.
2.	Select the voltage level (3.3V or 5V) using the onboard switch.
3.	Connect TX, RX, and GND to your microcontroller.
4.	Install CH340C drivers (if required for Windows users).
5.	Begin debugging or programming your microcontroller.

Repository Contents
•	Hardware Design Files
•	Schematic Diagrams
•	PCB Layout Files

Contributing
Contributions are welcome! Feel free to submit pull requests or report issues.
Contact
For questions or discussions, feel free to open an issue or reach out via LinkedIn or email me at Tecfield@live.com.

Merci pour votre attention.
Cordialement,
Siavash Alizadeh

