# Biometric Attendance System

This project is a biometric attendance system that utilizes the R307 fingerprint sensor and ESP8266 NodeMCU to register and track attendance using fingerprints. The system includes a web-based interface powered by XAMPP, allowing administrators to manage attendance records easily.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Components](#components)
- [Circuit](#circuit)

## Features

- **Real-time Attendance Tracking**: The system tracks attendance in real time, allowing for accurate monitoring of people entering or leaving the seating area.
- **Fingerprint Authentication**: Users can register their fingerprints using the R307 fingerprint sensor. The system verifies fingerprints for attendance tracking, ensuring secure and reliable identification.
- **Web-Based Interface**: The system includes a web-based interface powered by XAMPP, providing an easy-to-use platform for managing attendance records. Administrators can add and delete fingerprints, view attendance logs, and generate reports.
- **Visual and Audible Notifications**: LED lights and a buzzer provide clear visual and audible notifications when a seat becomes available or occupied, ensuring that users are aware of seating status changes.
- **Database Integration**: Attendance records are stored in a MySQL database, enabling efficient management and retrieval of attendance data. Administrators can access and analyze attendance records for reporting purposes.
- **Flexible Wi-Fi Configuration**: The system allows for easy configuration of Wi-Fi settings, enabling seamless integration into existing network environments. Administrators can specify the Wi-Fi network name and password in the code.
- **Easy Installation and Setup**: The project provides step-by-step instructions for installation and setup, ensuring a smooth setup process for users.
- **Open-Source and Customizable**: The project is open-source, allowing users to modify and enhance the system according to their specific requirements. The code is provided for further customization and expansion.

## Usage

The biometric attendance system offers several uses and applications across various domains:

- **Educational Institutions**: The system can be utilized in schools, colleges, and universities to automate attendance tracking for students and faculty members. It provides an efficient and reliable method of attendance management, eliminating the need for manual processes.
- **Corporate Offices**: Biometric attendance systems are widely used in corporate offices to streamline attendance recording for employees. It ensures accurate tracking of work hours, simplifies payroll processing, and reduces the chances of buddy punching or time theft.
- **Government Organizations**: Government offices and agencies can benefit from the biometric attendance system to monitor attendance of employees and ensure punctuality. It helps in maintaining accurate records and enhances transparency in attendance management.
- **Healthcare Facilities**: Hospitals, clinics, and healthcare facilities can utilize the system to track the attendance of healthcare professionals, staff members, and patients. It enables efficient scheduling and improves overall workflow management.
- **Gyms and Fitness Centers**: Biometric attendance systems can be implemented in gyms and fitness centers to manage member attendance and access control. It ensures only authorized individuals can access the facilities and tracks their attendance for billing and monitoring purposes.
- **Events and Conferences**: During events and conferences, the system can be used to manage attendee registration and track their presence at different sessions. It provides organizers with accurate attendance data and helps in ensuring efficient event management.
- **Co-working Spaces**: Co-working spaces can implement the biometric attendance system to monitor the usage of shared spaces and track the attendance of members. It enables efficient utilization of resources and provides transparent billing based on actual usage.
- **Research Laboratories**: Research institutions and laboratories can benefit from the system to track the presence of researchers, assistants, and other staff members. It ensures compliance with safety protocols and maintains records of laboratory access.
- **Manufacturing and Industrial Facilities**: Biometric attendance systems can be utilized in manufacturing and industrial settings to monitor employee attendance and manage shift schedules. It helps in maintaining a record of work hours and ensures appropriate staffing levels.
- **Security Access Control**: The system can also be integrated with access control systems to provide secure entry and exit for authorized individuals. It enhances overall security by restricting access to designated areas based on fingerprint authentication.

## Getting Started

Getting Started

To get started with the biometric attendance system, follow the steps below:

1. Install XAMPP

- Download and install [XAMPP](https://www.apachefriends.org/download.html), a cross-platform web server solution package.
- After installing XAMPP, activate the Apache and MySQL servers.

2. Set up the Web Application

- Locate the "biometricattendance" folder and place it in the following path: C:\xampp\htdocs.
- This folder contains the necessary files for the web-based interface.

3. Configure Wi-Fi Settings

- Open the Wi-Fi settings on your server[PC/laptop].
- Select "Internet Protocol Version 4" and activate the Static IP option.
- Set the IP address of your server to match your router's IP.

4. Update IP and Wi-Fi Settings in Arduino Code

- Open the Arduino code for the ESP8266 NodeMCU.
- Update the IP address in the code with the IP address of your laptop or computer.
- If you want to change the network settings, modify the Wi-Fi network name and password in the code.

5. Install Required Libraries and Boards

- Install the libraries provided in the Arduino IDE. These libraries are required for uploading the code to the ESP8266 NodeMCU.
- Make sure that the ESP8266 boards are available in the Arduino IDE.

**Note**: you can find neccassry libraries [here](Libraries).

6. Upload the Code to ESP8266 NodeMCU

- Connect the ESP8266 NodeMCU to your computer using a USB cable.
- Choose the correct port for the device in the Arduino IDE.
- Upload the code to the ESP8266 NodeMCU.

7. Install and Set Up the Server

- Open a web browser and enter the IP address of your laptop or computer.
- Follow the instructions displayed in the browser to set up the server.
- Create the necessary database for storing attendance records.

8. Start Managing Attendance

- Once the database is created, you can start adding and deleting people's fingerprints and monitor their attendance and departure.
- Open the following link in your web browser: http://192.168.29.200/biometricattendance/index.php

**Note**: this IP is my own you can modify it according to your needs and if you need a step by step guidence with images you will find it **[hear](Getting%20Started.pdf)**.

## Components

- 1 * ESP8266 NodeMCU
- 1 * R307 Fingerprint Sensor
- 1 * OLED Graphic Display 128x64 Serial I2C 0.96 inch

## Circuit

![Circuit Diagram](Circuit.PNG)
