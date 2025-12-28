# pps-pd-powersupply

A USB-C Power Delivery (PD) sink–based programmable power supply with PPS support, designed for embedded and power-electronics applications requiring negotiated, adjustable DC input from modern USB-C adapters.

---

## Overview

`pps-pd-powersupply` implements a USB-C PD sink system capable of dynamically negotiating voltage and current using the USB Power Delivery specification (PD 3.x with PPS). The project is intended for applications where a flexible, standards-compliant DC power input is required, including embedded systems, automotive electronics, development platforms, and power experimentation setups.

The design offloads USB PD protocol handling to a dedicated PD sink controller and exposes configuration and monitoring through an I²C interface. An external microcontroller selects power profiles, monitors system state, and enforces safety limits.

---

## Key Features

- USB Power Delivery sink operation with PPS support  
- Programmable voltage and current selection via I²C  
- Dynamic PDO/APDO negotiation with compliant USB-C chargers  
- Integrated safety mechanisms:
  - Over-voltage protection (OVP)
  - Under-voltage protection (UVP)
  - Over-current protection (OCP)
  - Over-temperature protection (OTP)
- External NMOS-based power-path control  
- USB Type-C cable orientation (CC flip) detection  
- Designed for integration with external host microcontrollers  


