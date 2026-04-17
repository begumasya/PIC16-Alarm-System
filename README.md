Project Title:
Smart Alarm System

Objective:
The aim of this project is to design and implement a physical circuit of an audible and visual smart alarm system using the PIC16F877A microcontroller. The system scans a 180-degree area and, if any object is detected within the scanned area, displays its distance on the LCD screen, illuminates a green LED, and continues scanning. If the object approaches closer than the predetermined distance, the alarm system is activated; the green LED turns off, the red LED turns on, the buzzer starts beeping, the system scanning stops, and the system locks itself. The alarm system remains active even when the object is moved away until the system password is entered via the keypad.

Module Distribution:

1. Distance Detection Module
2. LCD Display Module
3. Servo Motor Control Module
4. Alarm Module (LED and buzzer)
5. Keypad Security Module (optional)

Hardware:
The project will use the PIC16F877A microcontroller from the school’s experimental kits, and the system will be programmed using the CCS C language. The circuit design was tested and successfully implemented in Proteus using a potentiometer and a servo motor separately instead of a distance sensor. The goal is to convert this design into a physical circuit and implement it using a real distance sensor.

Workload Justification:
This project includes multiple modules and functions such as circuit design in the Proteus environment, microcontroller programming, sensor data processing, scanning control with a servo motor, data display via LCD, alarm system implementation, and password authentication. Task distribution was carried out based on these functions.

Task Sharing:
Begüm Asya EROĞLU: Development of Proteus circuit design, distance sensing, and LCD display modules.
Fırat Cem BAŞOĞLU: Development of servo motor control, alarm system (LED + buzzer), and keypad password authentication system.
