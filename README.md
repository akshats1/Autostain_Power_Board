# 🔌 Autostain Power Board

This repository contains all hardware design files for the **Autostain Power Board**, a custom PCB developed to manage and distribute power for the Autostain system. It provides regulated voltage lines and protection mechanisms for safe and efficient operation of motors, sensors, valves, or microcontrollers used in the autostaining process.

## 📁 Included Files

The provided ZIP archive includes:

- ✅ **Schematics** – Complete circuit diagrams (`.sch` / `.pdf`)
- ✅ **Gerber Files** – Fabrication-ready files for PCB manufacturing
- ✅ **BOM (Bill of Materials)** – Components list with part numbers and values (`.csv` / `.xls`)
- ✅ **Drill Files** – For CNC or automated PCB production
- ✅ **PCB Layout Preview** – Optional `.png` or `.pdf` showing the final board layout

## ⚙️ Specifications

| Parameter           | Value                            |
|---------------------|----------------------------------|
| Board Name          | Autostain Power Board            |
| Input Voltage       | [24V DC]                   |
| Output Rails        | [ 12 V,5 V 3.3V regulated]       |
| Max Current Output  | [2A per rail]              |
| Protection Features | Reverse polarity, overcurrent    |
| Connectors Used     | [Screw terminals, JST, etc.]|
| Board Dimensions    | [ 70mm x 70mm]              |
| Layers              | [ 2-layer FR4]              |

## ⚡ Key Features

- Regulated power output for multiple components (e.g., motors, valves)
- Onboard reverse polarity and short-circuit protection
- Clearly labeled power outputs for easy debugging and connection
- Compact layout for integration with autostainer enclosure
- Compatible with standard DC adapters or power bricks

## 🛠️ Tools Used

- **ECAD Software**: [KiCad ]
- **Gerber Output Format**: RS-274X
- **BOM Tool**: [KiCad built-in / BOM plugin]

## 🏗️ Assembly Instructions

1. **Order the PCB**  
   Upload the provided Gerber ZIP to any PCB manufacturer (e.g., PCBWay, JLCPCB).

2. **Procure Components**  
   Use the BOM to order parts from Digi-Key, Mouser, LCSC, or other vendors.

3. **Assemble the Board**  
   Solder components according to the silkscreen. Use flux and appropriate ESD protection.

4. **Test Voltage Rails**  
   Connect power supply and verify output voltages before connecting to downstream components.

## 📜 License

This hardware project is released under the **CERN Open Hardware License v2 – Permissive**.  
See the [LICENSE](./LICENSE) file for full terms.

