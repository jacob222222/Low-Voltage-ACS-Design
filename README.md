# Low-Voltage-ACS-Design
Low Voltage Access Control System Design

This project simulates the design and configuration of a basic low-voltage security system using access control panels, door sensors, and alarm relays for a small retail facility. It highlights the key components of technical security deployment.

🚀 Objectives

Simulate a real-world setup for access control and intrusion detection.

Configure badge access rules, door contacts, and alert escalation.

Use diagrams and configuration files to demonstrate system logic.

🔧 Tools Used

Bosch Configuration Manager

Access Professional Edition (APE) by Bosch (or simulation via Excel config tables)

Diagrams.net for system layout

Windows VM for hosting configuration environment

🧠 Skills Demonstrated

Understanding of low-voltage wiring principles

Access control panel programming and user provisioning

Alarm relay logic and input/output device mapping

Effective use of tools to simulate access violations and alerts

Documenting physical and digital installation procedures

📈 Project Documentation and Steps

Phase 1: Planning & Site Design

I designed a single-floor layout for a retail shop with 4 access points (main entry, staff door, stock room, manager office).

Mapped where the door contact sensors and request-to-exit buttons would be placed.

Phase 2: Device Configuration

Simulated Bosch access control panel configuration using a table for:

Badge credentials

Access schedules

Reader-to-door mapping

Created a visual layout showing cable paths and panel wiring.

Phase 3: Security Logic Programming

Wrote logic rules for:

Triggering an alarm if a door is held open for 30+ seconds

Sending alerts if access is denied more than 3 times within 5 minutes

Configured simulated relays for alarm outputs and linked to strobe lights/buzzer.

Phase 4: System Testing

Conducted simulated access events:

Successful entry

Denied access (unauthorized badge)

Door held open

Logged event triggers and verified alert behaviors

Phase 5: Documentation

Created a visual map of device connections

Wrote an operational handbook for retail store employees

Logged commissioning report and compliance verification checklist

📸 Screenshots

(coming soon...)

📁 Project Files #files are not included at the moment. They will be pushed later. This project only show what I, Jacob did.

layout/ – Floor plan and device layout

config/ – Configuration tables and access control rules

logs/ – Simulated access logs and incident responses

screenshots/ – Visuals of setup and configuration process

✅ Key Outcomes

This project aligns with practical industry requirements in:

Designing, installing, and maintaining low-voltage security systems

Creating structured access permissions

Providing field-ready documentation and compliance reporting

Created by Jacob Dukuly 
