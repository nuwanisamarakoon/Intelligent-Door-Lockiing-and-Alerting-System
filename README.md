# Security Door Locking and Alerting System with Biometric Access Control

<img src="https://github.com/Ashani-Sansala/Intelligent-Door-Locking-and-Alerting-System/assets/85635476/2683a8ba-9c1b-4dcc-8f6d-46149c0b4310" width="400"/>
<img src="https://github.com/Ashani-Sansala/Intelligent-Door-Locking-and-Alerting-System/assets/85635476/be4afcd0-16e0-4d0b-b5a3-7f2e72bd2e4d" width="200" height="300"/>
<img src="https://github.com/Ashani-Sansala/Intelligent-Door-Locking-and-Alerting-System/assets/85635476/bb7dee25-cd12-4b2c-948b-9d04e539a130" width="400"/>

## Introduction

The Security Door Locking and Alerting System is a cutting-edge hardware project developed as part of our first-year hardware project. This project aims to provide secure access control to sensitive areas, specifically tailored for a bank vault. The system combines advanced biometric authentication techniques with intelligent automation to ensure foolproof security.

## Features
Biometric Authentication: The system utilizes both fingerprint and face recognition to authenticate authorized personnel. Access to the vault is only granted when three designated personnel (bank manager, vault officer, and security officers) are successfully authenticated.

Time-Restricted Access: The system allows access to the vault only during predefined time periods. Outside of these hours, the vault door remains locked even for authorized personnel.

ESP32 Board and ESP32 Cam Module: The core of the system is powered by the ESP32 board and the ESP32 Cam module, providing robust processing capabilities and connectivity options.

GSM Module: In the event of an unauthorized entry, the system triggers an alert and sends a warning message to designated personnel via GSM communication, ensuring immediate attention and response.

PIR Sensor: The Passive Infrared (PIR) sensor detects motion within the vicinity of the vault, allowing the system to identify unauthorized access attempts.

RTC Module: The Real-Time Clock (RTC) module ensures accurate timekeeping, enabling time-based access restrictions.

Machine Learning for Face Recognition: The system incorporates machine learning techniques for efficient face recognition, enhancing the security and accuracy of the authentication process.

Autonomous Operation: The system's intelligent design enables autonomous operation, reducing the need for manual intervention and ensuring reliability.

## How it Works
Authentication Process: Authorized personnel need to undergo a two-step authentication process, involving both fingerprint and face recognition. Only when all three designated individuals are successfully authenticated, the vault door is unlocked.

Time-Based Access: The system checks the current time against predefined access periods. If the current time falls within the allowed time range, the door can be unlocked upon successful authentication.

Unauthorized Entry Alert: In case of an unauthorized entry attempt, the system triggers an alert with a warning sound to deter intruders. Simultaneously, it sends an immediate message to designated personnel stating 'Unauthorized Entry' via GSM communication.

Prompt Response: The system further initiates phone calls to designated personnel, ensuring swift and prompt response to any security breach.

## Project Status
The Security Door Locking and Alerting System is a successfully completed first-year hardware project. We have achieved our primary objectives of creating a secure and reliable access control system using biometric authentication. The system has been demonstrated to and appreciated by our Dean, encouraging us to continue pushing boundaries in our future endeavors.

## Future Enhancements
As we move forward, we aim to enhance the system with the following features:

Integration of advanced AI algorithms to improve biometric recognition accuracy.
Implementing multi-factor authentication for added security layers.
Developing a user-friendly mobile application for remote monitoring and access management.
Exploring cloud-based storage for secure backup and data management.
Repository Structure
/src: Contains the source code for the Security Door Locking and Alerting System.
/documentation: Includes project documentation, circuit diagrams, and hardware component specifications.
/media: Holds images and videos related to the project.
How to Contribute
We welcome contributions and suggestions to improve the Security Door Locking and Alerting System. If you have any ideas, bug fixes, or enhancements, feel free to open an issue or submit a pull request.

## Acknowledgments
We would like to express our gratitude to our incredible advisors and supporters:
Mr. BH Sudantha (Dean of the Faculty of IT) for his guidance,
Prof. Asoka Karunananda,
Dr. Thushari Silva (Head of Department of Computational Mathematics),
Mrs. Nipuni Chandimali (supervisor),
Mr. Daham Alwis,
Mr. Manoj Anushka for guiding us throughout the project and inspiring us to innovate. We also extend our thanks to the open-source community for providing valuable resources that helped us in creating this project.
