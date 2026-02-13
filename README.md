# RFID-Access-Control-Arduino
RFID-based access control system using Arduino and RC522 module

📌 Overview

A simple Arduino-based access control system using an RFID RC522 module.
The system reads RFID card UIDs and grants or denies access using LED indicators.

🟢 Green LED → Access Granted

🔴 Red LED → Access Denied

This project demonstrates basic embedded systems concepts and RFID authentication logic.

⚙️ Components

Arduino UNO

RFID RC522 Module

RFID Card/Tag

Breadboard & Jumper Wires

2 LEDs

2 × 220Ω Resistors

🔌 Connections

RFID → Arduino

SDA → D10

SCK → D13

MOSI → D11

MISO → D12

RST → D9

3.3V → 3.3V

GND → GND

LEDs

Green LED → D3 (via resistor)

Red LED → D4 (via resistor)

💡 Working

The RFID reader scans a card and compares its UID with an authorized UID stored in the code.
Authorized cards are allowed access, while others are denied.

🛠️ Software

Arduino IDE (Embedded C)

👩‍💻 Author

Abina Abey

