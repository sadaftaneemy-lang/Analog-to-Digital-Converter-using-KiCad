# Analog to Digital Converter using KiCad

## 📌 Self-Initiated Project
This is a self-initiated project created to explore and apply concepts in electronics through hands-on design and simulation

## What is KiCad ??
KiCad is a free, open-source Electronic Design Automation (EDA) tool used to design electronic circuits and Printed Circuit Boards (PCBs). 

## What is an AC to DC Converter 
An Analog to Digital Converter (ADC)  is a circuit that converts a continuous analog signal (like temperature, sound, voltage, sensor output) into a digital binary number that digital systems can process

<img width="687" height="341" alt="image" src="https://github.com/user-attachments/assets/7308fcc0-668c-415b-a7d8-abcf1fe6790a" />

<img width="960" height="353" alt="image" src="https://github.com/user-attachments/assets/93c7d376-17a4-4972-b5b1-7f9500fc88c3" />

## 🔰 Applications
An ADC is used wherever real-world analog signals must be converted into digital form for processing by digital systems like microcontrollers, DSPs, processors, or computers.

1. Audio Processing
   Microphones produce analog signals.

<img width="1100" height="619" alt="image" src="https://github.com/user-attachments/assets/3e51e066-930b-4386-86ff-c22ebbfbc9b0" />

ADC converts:
- Voice
- Music
- Sound waves, into digital data.

Which is used  in:
- Mobile phones
- Voice recorders
- Bluetooth devices
- Digital audio systems

2. Medical equipments
  Biomedical signals are analog.

     <img width="2313" height="1596" alt="image" src="https://github.com/user-attachments/assets/fa21d14c-4173-478b-be69-f9ceaaf23a01" />
ADC is used in:
- ECG
- EEG
- Patient monitoring systems
- Digital thermometers

## 🤖 Advantages
❉ ADCs help digital systems accurately interpret continuously varying real-world signals such as temperature, sound, pressure, and light.

❉ They reduce the effect of external noise because digital signals are more reliable and less sensitive to interference than analog signals.

❉ ADCs make it possible to store analog information in digital memory devices for long-term usage and analysis.

❉ They enable fast processing of signals using microprocessors, DSPs, and embedded controllers.

❉ ADCs improve system flexibility because digital data can be easily modified, encrypted, compressed, or transmitted over networks

## 🛰️ ADC Flow
1. Analog input is applied
2. ADC samples the signal
3. Quantizes it into levels
4. Produces binary output

# 🔋 KiCad 
KiCad is an open-source EDA (Electronic Design Automation) software used for:
1. Schematic design
2. PCB layout
3. Simulation
4. Gerber generation
5. 3D PCB visualization

## 🔗🔗 Installation
I referred to this video during setup:
- [https://youtu.be/JZitbgEbCHU?si=QlpFLPeTkP8un1ju]

# 📐 About the project
This project presents the design and implementation of an AC to DC Converter PCB using KiCad. The circuit converts an alternating current (AC) input into a regulated direct current (DC) output using a bridge rectifier configuration, filtering capacitor, resistor network, and LED indication circuit.

The project was designed completely in KiCad, including:

   - Schematic design
   - PCB layout
   - Routing
   - Footprint assignment
   - Ground plane generation
   - 3D visualization preparation

This project demonstrates basic power electronics concepts along with practical PCB design workflow using an industry-standard open-source EDA tool.

## 🧩 Components Used

Component	Description
D1–D4	1N4007 Rectifier Diodes
C1	Filter Capacitor
R1, R2	Resistors
D5	LED Indicator
J1	AC Input Terminal
J2	DC Output Terminal

## 🔌 Working Principle

The AC voltage is applied through the input connector. The four diodes connected in bridge rectifier configuration convert the alternating current into pulsating DC. The capacitor filters the ripple content and provides a smoother DC output voltage. The resistor and LED combination acts as an output power indicator. The final DC output is obtained at the output terminal connector.

## 📂 Project Workflow

➤ Schematic Design

➤ ERC Verification

➤ Footprint Assignment

➤ PCB Layout Design

➤ Routing and Ground Fill

➤ DRC Check

➤ Gerber File Generation

## 🎯 Applications

⚡ Power supply circuits

⚡ Embedded systems

⚡ Educational electronics projects

⚡ PCB design practice

⚡ Low-power DC supply applications

## 🚀 Learning Outcomes

Through this project, the following concepts were learned:

- PCB designing using KiCad
- Schematic capture
- Component footprint mapping
- PCB routing techniques
- Bridge rectifier operation
- Power supply circuit fundamentals
- Design Rule Check (DRC) and ERC validation

## 📸 Project Images

Include:

**1. Schematic screenshot**

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/9f07bc3f-6e86-4c14-a06e-76533cef2000" />

**2. PCB layout screenshot**

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/a580a488-2be6-4b81-91d6-d915f25d3a2b" />

## Acknowledgement

This project was developed for learning and practice purposes to understand PCB design flow and AC to DC conversion using KiCad. External tutorials and documentation were referred to during installation and project development.

