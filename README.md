# I2C-enabled USB-C Power Supply

![Board](https://github.com/user-attachments/assets/0ff5ac3c-2cdf-4d28-b5ed-92fe5b61096c)

## Highlights

- USB-C Power Delivery breakout board with **PPS support**
- Programmable, regulated output from **5 V to 24 V**
- Dynamic voltage and current negotiation with **PD-compliant chargers**
- Simple **I²C interface** for configuration and real-time monitoring
- Built-in protection: **OVP, UVP, OCP, and OTP**

---

## Description

By leveraging the **Programmable Power Supply (PPS)** capability of USB-C PD, the board provides a wide, adjustable voltage range without requiring custom USB-PD firmware on the host microcontroller.

A **standalone PD sink controller** manages all power negotiation with the charger, exposing a clean and lightweight **I²C interface** for voltage, current, and status control. This keeps firmware simple while maintaining full standards compliance.

Designed with flexibility and safety in mind, the board integrates essential protection and monitoring features, making it well-suited for embedded systems, power electronics prototyping, and USB-C PD experimentation.

---

## Easy I²C Control

All configuration and monitoring is performed over I²C by the given code. No separate configurations are required:

- Set output voltage and current limits
- Read negotiated PD contract parameters
- Monitor fault and protection status in real time

---

## Specifications

- **Output Voltage:** 5 V – 24 V (PPS)
- **USB-PD Support:** PD 3.1 with PPS
- **Protection Features:** OVP, UVP, OCP, OTP
- **Input Source:** USB-C PD-compliant charger

---
## Author

**Sujin Shakya**  
GitHub: https://github.com/sujinshakyaut 


