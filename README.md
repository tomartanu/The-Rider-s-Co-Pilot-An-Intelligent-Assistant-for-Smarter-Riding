# The-Rider-s-Co-Pilot-An-Intelligent-Assistant-for-Smarter-Riding
The Rider’s Co-Pilot is an Arduino-based smart helmet system designed to improve motorcycle safety through real-time monitoring and intelligent ignition control. The system ensures that a bike starts only when essential safety conditions are met, acting as an automated safety assistant for riders.

# Key Features
- Helmet Detection – Engine starts only when the helmet is properly worn
- Alcohol Detection – Prevents ignition if alcohol is detected
- Drowsiness Detection – Monitors rider fatigue using Open CV and alerts or stops the engine

# How It Works
The system consists of two main units:
- Helmet Unit (Transmitter): Collects rider data using sensors and sends it wirelessly
- Bike Unit (Receiver): Processes the data and controls ignition using a relay

The engine is allowed to run only when all safety conditions are satisfied. If any unsafe condition is detected, the system immediately restricts or stops the engine.

# Tech Stack & Components
- Arduino UNO
- Raspberry Pi
- LoRa Module
- IR Sensor
- MQ-3 Alcohol Sensor
- Relay Modul

# Objective
To reduce road accidents caused by negligence (no helmet, alcohol consumption, fatigue) by enforcing safety measures automatically using embedded systems and IoT concepts.
