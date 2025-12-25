I developed a smart electronic patient queue display system to improve appointment handling and patient flow in medical channeling centers and hospitals. The main objective of this project was to automate patient number calling, reduce manual errors, and create a clear and organized waiting experience.
The system is designed with two separate hardware units: a transmitter and a receiver, connected through RS485 wired communication to ensure reliable and long-distance data transfer in noisy medical environments.

Transmitter Unit
The transmitter unit is built using an ESP32 microcontroller and functions as the control interface for medical staff. Patient numbers can be entered, increased, or decreased using a 4×4 keypad, and the current status is displayed in real time on OLED screens. Once a patient number is confirmed, it is instantly transmitted to the display unit.

Receiver Unit
The receiver unit is based on an Arduino Nano and is responsible for displaying patient numbers in the waiting area. The numbers are shown on seven-segment displays, controlled using 74HC595 shift register ICs to minimize microcontroller pin usage and ULN2803A driver ICs to safely handle the required current for the displays. The receiver also includes LED indicators to show active display modes and a buzzer alert that activates whenever the displayed number changes, ensuring patients are notified both visually and audibly.

Key Highlights
•	Reliable RS485 communication for long-distance and noise-resistant operation
•	Efficient display control using 74HC595 shift registers
•	Safe and high-current display driving with ULN2803A ICs
•	Real-time visual feedback using OLED displays
•	Audio and visual alerts for patient notifications
•	Suitable for multiple counters or doctors

Outcome
This project provides a practical solution for patient queue management, improving operational efficiency for medical staff while enhancing clarity and comfort for patients in waiting areas.


https://github.com/user-attachments/assets/25a3033f-be08-41c0-8cb7-9a5eff674362

