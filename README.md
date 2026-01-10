# ESP32 Wireless Thermometer

## Overview
This project is a **custom, battery-powered ESP32-based wireless thermometer** designed for BBQ and probe-based temperature monitoring.

The goal is to build a **robust, safe, and manufacturable device** suitable for real-world use, not a development board or a proof-of-concept. The design prioritizes reliability, serviceability, and clear engineering tradeoffs over extreme miniaturization or feature creep.

---

## Project Goals
- Battery-powered operation using a single-cell Li-ion / LiPo battery
- 24+ hour runtime under typical use
- In-place battery charging via USB-C (power only)
- Wireless connectivity (Wi-Fi required, BLE optional)
- OTA firmware update capability
- Support for multiple external thermistor probes
- Safe hot-plugging of all external connectors
- Outdoor and kitchen-safe electrical robustness
- Aluminum enclosure compatibility with minimal machining tools
- Low-cost, reproducible manufacturing
- Friendly to both SMT assembly and hand soldering

---

## Design Philosophy
This project is guided by the following principles:

- **Safety first**  
  All external connections must tolerate hot-plugging, static discharge, and user error without damaging the device.

- **Manufacturable by design**  
  Components and footprints are selected with real-world assembly in mind, favoring widely available parts and avoiding unnecessary complexity.

- **Debuggable and understandable**  
  The design should be easy to inspect, measure, and troubleshoot without specialized equipment.

- **Incremental improvement**  
  Revisions build on known-good designs, preserving proven circuits while improving specific areas as needed.

---

## Non-Goals
The following are explicitly out of scope:
- USB data or USB-PD support
- Power-bank or device-charging functionality
- Ultra-miniaturized or wearable form factors
- Dev-board style layouts
- Feature-driven complexity that compromises reliability

---

## Repository Structure
This repository contains the hardware design files and supporting documentation for the project.

Typical contents include:
- KiCad schematics and PCB layouts
- Project-local symbol and footprint libraries
- Design notes and revision history
- Manufacturing and assembly references

Generated outputs (Gerbers, fabrication files, temporary caches) are not tracked unless explicitly required.

---

## Status
This repository contains an evolving hardware design with multiple revisions. Earlier revisions serve as validated references; newer revisions focus on improved power handling, manufacturability, and long-term reliability.

---

## License
This project is intended for personal, educational, and hobbyist use. Licensing details may be added as the design matures.

---

## Acknowledgements
This project draws on common, well-established embedded hardware design patterns and prioritizes practical engineering over novelty.
