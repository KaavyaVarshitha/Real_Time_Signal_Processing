# Real Time Signal Processing and Peripheral Control on FM4 Board

## Project
This embedded systems project involves implementing multiple signal processing and peripheral control tasks on the FM4 microcontroller board using Embedded C. The project consists of three main modules:

### 1. Cosine Signal Generation:
A cosine waveform of frequency 666.66 Hz is generated using a lookup table. The waveform is output through the FM4 audio code at a sampling rate of 8 kHz. Verification is done via Visual Analyzer (VA).
![image](https://github.com/user-attachments/assets/dfe170e2-4960-4782-926a-1c781b0f7b22)

![image](https://github.com/user-attachments/assets/1b9dbb92-f889-42b2-90b8-316b89313ee8)

### 2. Switch Triggered Signal and LED Control
When the user switch is pressed, the system activates a red LED on the RGB module and generates the cosine waveform for exactly 5 seconds. The waveform duration is controlled via a counter calculating 40,000 samples for 5 seconds at 8 kHz sampling rate. After the duration, the LED turns off and signal stops.

### 3. DOT Product Using UART
Two arrays containing values [1, 2, 3, 4, 5] are multiplied using a dot product operation. The result is output to the UART serial monitor, showcasing interaction between embedded computation and communication peripherals.
![image](https://github.com/user-attachments/assets/404f88c6-11aa-4330-98dd-6aa0aec006eb)

## Authors

Solution|Author(s)
--------|---------
FM4 Signal Control | [Kaavya Varshitha Raman Shantha](https://github.com/KaavyaVarshitha) 

## Version history

Version|Date|Comments
-------|----|--------
1.0|Feb 2025|Final
