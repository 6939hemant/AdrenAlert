# AdrenAlert
A wearable system that detects adrenaline in blood and sends distress alerts.
AdrenAlert: Blood-Based Adrenaline Detection & Distress Alert System

By Hemant Khemraj Khekare | Nagpur, India

---
Overview :-

AdrenAlert is a skin-mounted wearable system that detects adrenaline levels in blood and automatically sends a distress signal to local authorities or emergency contacts. This device aims to silently communicate danger or high-stress situations, especially in cases where the user cannot verbally ask for help.

---

Problem Statement:-

Millions of people encounter life-threatening or high-stress situations—harassment, assault, medical emergencies—where speaking out or using a phone is not possible. The body naturally produces adrenaline (epinephrine) in such cases. Detecting this hormone in real-time could act as a biological SOS, enabling automated emergency responses without requiring user interaction.

---
Proposed Solution:-


Design a miniaturized wearable device that:-
Samples blood via a microneedle biosensor.
Measures adrenaline concentration electrochemically.
Sends real-time data to a microcontroller (ESP32).
Automatically transmits alerts via Bluetooth or GSM when adrenaline crosses a critical threshold
Optionally integrates with a mobile app to display live data and send alerts with location

---

System Diagram:-

i have designed it by myself 

---
Key Components:-

Component	Role:-

Microneedle sensor	Extracts small blood samples for analysis
Electrochemical sensor	Detects adrenaline concentration via enzyme reaction
Signal amplifier (LMP91000)	Boosts weak biosensor signal
Microcontroller (ESP32)	Processes signal, triggers alert, handles BLE/WiFi
GSM Module (SIM800L)	Optional direct alert via SMS if smartphone unavailable
LiPo Battery + TP4056	Compact power supply and charger
Android/iOS App	Shows adrenaline levels, triggers emergency alerts

---
Working Principle:-
1. Detection: The biosensor detects adrenaline in blood using enzyme reactions.
2. Processing: A low-noise amplifier feeds signal into an ESP32, which checks levels.
3. Trigger: If adrenaline spikes, ESP32 sends a signal via BLE or GSM.
4. Alert: App or module sends a pre-defined SOS message and GPS location to local authorities or emergency contacts.
---
Innovation & Uniqueness:-
Detects adrenaline from blood, not just sweat (rare in wearable tech)
Automatically sends alerts without user input
Designed to be small, wearable, and real-time
Can help in crime prevention, health monitoring, and emergency response

---

Impact Potential :-
This technology could:
Help women and children silently call for help
Assist in elder care and mental health monitoring
Be used by defense or rescue forces under stress

---
Development Status:-
Research phase complete
Hand-drawn system design completed
Component selection done (next:prototyping & circuit building)
Paper drafting in progress for submission to IJRASET

---

Future Plans
Build real prototype with custom PCB
File a provisional patent for the design
Submit research paper to IJRASET
Expand into wearable health-tech applications
Collaborate with labs at institutions like MIT for validation and scaling

---
Author's Note
> "I had no background in electronics or coding. But I had a problem to solve, and I learned everything step by step — from sensor chemistry to microcontroller programming. This project taught me that innovation doesn’t begin with knowing; it begins with caring."
> 
— Hemant Khemraj Khekare
