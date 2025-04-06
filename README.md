#📡 Office Networking Automation
This project is a simulation of a smart office setup using Cisco Packet Tracer. It integrates networking components, IoT devices, sensors, and automation logic to create a responsive and energy-efficient office environment.

#🏢 Project Overview
The smart office is divided into several interconnected zones:

1. Entrance Room

2. Main Room

3. Conference Room

4. Break Room

5. Safety Room

6. Server Room

Each room is equipped with devices and components that communicate over a network to achieve automation and security goals.

#💡 Key Features
1. Smart Door Access (Entrance Room)
Uses RFID card system for access control.

Valid RFID card triggers door to open; fake cards are rejected.

Controlled via an RFID reader and linked to the main server.

2. Energy Management (Main & Conference Room)
Solar panels generate power, stored in a battery system.

Power is distributed to Solar MCU and devices like fans and lights.

Conference room devices (e.g., light, solar fan) are managed via Solar Power MCU.

3. Smart Appliances (Break Room)
Motion detector triggers a smart fan and coffee maker when presence is detected.

Music player and Bluetooth speaker add ambient features for breaks.

4. Fire Safety System (Safety Room)
Equipped with Fire Monitor (IoT2) and IoT sensors.

If fire (Thing IoT1) is detected, an alert is triggered:

Siren goes off.

Fire sprinkler activates.

Notifications are sent via server to connected devices (phone/laptop).

5. Server & Network Control (Server Room)
Smart_Office_Server handles data flow and device control.

Devices connect via WRN300N Smart Office Router and Cable Modem.

Cluster0 cloud manages remote access/control simulation.

#📡 Devices and Components
Microcontrollers (MCUs): Control fans, lights, safety devices.

IoT Devices: Fire sensors, sprinklers, motion detectors.

Communication: Wi-Fi via router; server-client over a LAN.

Power: Solar panel + battery management system.

#🔧 Tools Used
1. Cisco Packet Tracer (.pkt file)

2. IoT Components and Networking Devices

3. Solar Power Simulation

4. Sensor-based Automation

#🧪 Scenarios Demonstrated
Scenario	Outcome
Fake RFID card	Door stays locked
Valid RFID card	Door opens
Fire detected in Safety Room	Siren + Sprinkler activate
Presence in Break Room	Fan and Coffee Maker activate automatically
Solar energy zero (night)	Devices rely on stored battery power
#📁 Files Included
office networking.pkt: Main simulation file

Report_Cisco_Packet_73.docx/pdf: Project documentation

Screenshots: Visual reference of setup and simulation states

#✅ How to Run
Open Cisco Packet Tracer.

Load the office networking.pkt file.

Power on all devices.

Test automation flows by:

Swiping RFID cards.

Triggering motion sensors.

Simulating fire by toggling the IoT Thing device.

Observe system reactions and server logs.

#📌 Notes
Ensure all IoT and network components are online for accurate simulation.

The solar panel power may read 0 W at night simulation (second screenshot), demonstrating dependency on battery.

#🧠 Authors & Contributors
Smart automation designed using Cisco Packet Tracer for learning and simulation purposes.
