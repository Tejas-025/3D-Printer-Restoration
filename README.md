# 3D-Printer-Restoration

A restoration and development was carried out on an almost scrapped Leapfrog Creatr 3D printer , in 3 phases , where we developed the printer 


Open-Source Development of an Advanced Klipper-Based 3D Printing Platform


Overview

This repository documents the design, development, integration, and validation of an advanced, open-source 3D printing platform built around Klipper firmware, Moonraker API, and Mainsail UI.

The project focuses on upgrading and repurposing existing hardware into a modern, feature-rich system aligned with current industry and research standards while keeping the solution cost-effective, modular, and extensible.

This work is the result of hands-on system-level engineering, combining firmware development, IoT integration, motion control optimization, and reliability engineering.

Project Objectives

1. Upgrade legacy and custom-built 3D printers to modern firmware and control stacks

2. Implement real-time motion control enhancements using Klipper

3. Enable remote monitoring, control, and diagnostics

4. Design a modular configuration architecture for easy future expansion

5. Maintain open-source compatibility and reproducibility

Key Technical Contributions

🔧 Firmware & Control

1. Migration to Klipper firmware with custom configuration tuning

2. Integration of Moonraker API for robust client communication

3. Structured printer.cfg with modular includes for scalability

⚙️ Motion & Print Quality Enhancements

1.Prepared architecture for:

2.Input Shaping

3.Pressure Advance

4.Resonance analysis (ADXL / Sonar-based workflows)

5.Stable high-speed printing on constrained hardware

🌐 IoT & Remote Access

1.Secure API-based printer control using Moonraker

2.Remote monitoring via Mainsail dashboard

3.Integration and evaluation of third-party services (OctoEverywhere, Sonar)

4.Websocket reliability analysis and mitigation

📷 Monitoring & Timelapse

1.Webcam integration using Crowsnest

2.Timelapse workflow integration and testing

3.Network-aware webcam routing and stability fixes

 
 
Modular & Future-Ready Design

Clean separation of:

Firmware logic

Macros

Add-ons (timelapse, sonar, future MMU/toolchanger support)

Designed for future expansion:

Multi-material systems

Tool changers

Advanced sensor feedback



🛠 Hardware Platform

Custom and repurposed Cartesian / Delta printers

Raspberry Pi–based control (tested on Pi 3B+)

Standard 3D printer electronics and stepper drivers

USB and camera peripherals



🧪 Engineering Challenges Addressed

Websocket instability under constrained hardware

Network interface reliability and IP fluctuation handling

Concurrent service load optimization

API access control and CORS handling

Real-time monitoring without compromising print stability



Results & Outcomes

Successfully transformed legacy hardware into a modern, networked 3D printer

Achieved stable remote operation under real-world constraints

Established a robust baseline for high-speed and intelligent printing

Created a reusable architecture applicable to multiple printers


*Open-Source Philosophy*

This project is developed with a strong belief in:

Transparency

Reproducibility

Community-driven improvement



All configurations and workflows are intentionally kept readable, modular, and hackable.

🚧 Current Status

Core system: ✅ Stable

Remote monitoring: ✅ Functional

Timelapse & sensor integrations: 🟡 Ongoing optimization

Advanced motion tuning: 🟡 Planned

Multi-tool / MMU expansion: 🔜 Future work


Acknowledgements  

This project builds upon the incredible work of:

Klipper

Moonraker

Mainsail

Crowsnest

Open-source 3D printing community

Thanks for your support while building all the good stuff
