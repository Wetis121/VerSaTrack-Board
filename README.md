# VerSaTrack Board

Open-source STM32F407 development board designed for industrial automation, IoT applications, robotics, and embedded systems.

The VerSaTrack Board integrates high-speed communication, wireless connectivity, GPS positioning, external storage, and a graphical user interface into a compact hardware platform. This repository provides complete open-source hardware design files, including schematics, PCB layout, BOM, manufacturing files, and firmware examples.

---

# Features

- STM32F407VGT6 ARM Cortex-M4 MCU
- W5500 10/100 Mbps Ethernet
- ESP32-C3 Wi-Fi Module
- NEO-6M GPS Module
- 2.4-inch SPI TFT LCD with Touch Interface
- USB Type-C Programming & Communication
- microSD Card Interface
- Dual SPI Flash Memory
- Industrial-grade Expansion Headers
- Open Hardware Design Files
- Altium Designer Project

---

# Hardware Specifications

| Item | Description |
|------|-------------|
| MCU | STM32F407VGT6 |
| Ethernet | W5500 |
| Wireless | ESP32-C3 Wi-Fi |
| GPS | NEO-6M |
| Display | 2.4" SPI TFT LCD |
| Touch | Capacitive Touch |
| Storage | microSD + Dual SPI Flash |
| USB | USB Type-C |
| Programming | USB Serial |
| Operating Voltage | 5V USB |
| PCB | 4-Layer FR-4 |

---

# Hardware Block Diagram

```
                 +-----------------------+
                 |     STM32F407 MCU     |
                 +----------+------------+
                            |
      +---------+-----------+-----------+-----------+
      |         |           |           |           |
      |         |           |           |           |
  Ethernet     Wi-Fi       GPS      Display      Storage
   W5500     ESP32-C3    NEO-6M   2.4" TFT LCD  microSD
                                           |
                                      Touch Panel

```

---

# Repository Structure

```
.
├── Hardware
│   ├── Altium_Project
│   ├── Schematic
│   ├── PCB
│   ├── BOM
│   ├── PDF
│   └── Manufacturing_Files
│       ├── Gerber
│       ├── Pick_and_Place
│       └── Assembly_Drawings
│
├── Firmware
│   ├── STM32CubeIDE
│   ├── Drivers
│   ├── Libraries
│   └── Examples
│
├── Images
│
├── Datasheets
│
├── Documentation
│
└── README.md
```

---

# Hardware Preview

> *(Add PCB images here)*

| Top View | Bottom View |
|----------|-------------|
| ![](Images/top.png) | ![](Images/bottom.png) |

---

# Software

- STM32CubeIDE
- STM32 HAL
- FreeRTOS (Optional)
- FATFS
- LWIP
- ESP32 AT Firmware

---

# Applications

- Industrial Automation
- IoT Gateway
- Robotics Controller
- Data Logger
- GPS Tracking
- Ethernet Communication
- Human Machine Interface (HMI)

---

# Getting Started

1. Clone this repository

```
git clone https://github.com/Wetis121/VerSaTrack-Board.git
```

2. Open the Altium Designer project.

3. Generate Manufacturing Files if required.

4. Open the firmware using STM32CubeIDE.

5. Compile and flash the firmware.

---

# License

This project is released under the MIT License.

Feel free to use, modify, and contribute to this project.

---

# Author

**Wetis Klingram**

Embedded Hardware Engineer

GitHub: https://github.com/Wetis121
