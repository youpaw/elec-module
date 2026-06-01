# FLIPPER 42 — Electronics Project

A custom device inspired by the Flipper Zero, capable of reading, cloning, and emitting NFC & RFID signals. It features an external coaxial antenna, optional infrared transmission, a custom firmware display, and SD card storage for saved data.

---

## Overview

| Feature | Description |
|--------|-------------|
| **Controls** | 5-button navigation: ◄ ▼ ● ▲ ► (Left, Down, Select, Up, Right) |
| **Power** | 5V DC supply |
| **Storage** | SD card module for firmware and saved signals (NFC dumps, etc.) |
| **Antenna** | External coaxial antenna |
| **Additional** | IR emitter for infrared signal transmission |

---

## Components

### NFC Reader
**IC:** ST25R3916B-AQWT  
High-performance NFC frontend supporting reader/writer and card emulation modes.  
📄 [Datasheet](https://www.st.com/resource/en/datasheet/st25r3916b.pdf)
### RFID Reader
**IC:** EM4095  
125 kHz RFID transceiver for LF tag reading and writing.  
📄 [Datasheet](https://www.emmicroelectronic.com/sites/default/files/products/datasheets/em4095_ds.pdf)

### SD Card Module
**Part Number:** 1040310811 (Molex)  
Micro SD card socket for firmware storage and signal database.  
📄 [Datasheet](https://www.molex.com/en-us/products/part-detail-pdf/1040310811?display=pdf)

---

## Materials

| Qty | Component | Part Number / Symbol | Notes |
|-----|-----------|----------------------|-------|
| 1 | NFC Transceiver | ST25R3916B-AQWT | |
| 1 | RFID Transceiver | EM4095 | 125 kHz |
| 1 | SD Card Socket | 1040310811 | Molex |
| 1 | Coaxial Antenna | — | External |
| 1 | IR LED / Transmitter | — | Optional |
| 1 | Display Module | — | For custom firmware UI |
| 5 | Tactile Switches | — | Navigation buttons |
| — | Power Regulation | — | 5V input |

