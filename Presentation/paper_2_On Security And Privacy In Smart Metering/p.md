---
marp: true
title: 
theme: gaia
paginate: true
---
# Paper 2 : On Security And Privacy In Smart Metering System
- Key Topics: Energy theft, theft detection methods, physical security implementations
---
# Energy Theft
- Occurs when customer manipulate metering device physically or in case of smart meters, manipulates the power consumption data(pcd) sent to utility.
- In  meters theft occurs in the following ways:
    - Mechanical tampering
    - Meter bypass 
    - Hacking or alerting memory
--- 
# Theft Detection 
- Using PCD it is possible to determine the energy consumption of customer over a period of time. Using data analytics, or machine learning algorithms, suspicious patterns can be detected.

- Types:
    - Classification based : Train a classifier using suspicious and non-suspicious data samples.(fuzzy logic , etc can also be used.)
    - State based : Use devices like rfid tags and wireless sensors like camera etc.

---
# Security Measures
- Housing Integrity: Using easily deformable screws/clips, have tampering seals that break easily.
- Lack of physical switches: Decreases interaction with meter
- Firmware and authorization : Regular Updates to hold integrety of device.
- Communication Encryption

