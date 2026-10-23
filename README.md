# 48V-UGV-Power-Distribution-Board
48 V high-current power distribution PCB for a 4-wheel UGV, featuring MOSFET high-side switching and a two-layer KiCad design.
# 48 V UGV Power Distribution Board

### Project Overview

This project focuses on the electrical design and PCB layout of a high-current Power Distribution Board (PDB) for a four-wheel autonomous Unmanned Ground Vehicle (UGV) intended for vineyard applications.

The objective is to develop a compact power distribution architecture capable of supplying multiple motor controllers and auxiliary loads from a nominal 48 V battery system.

### Key Design Specifications

| Parameter | Design Target |
|---|---|
| Input Voltage | 48 V DC nominal |
| System Power | Approximately 5 kW |
| Maximum Bus Current | 100 A |
| Motor Controller Channels | 4 |
| Switching Architecture | P-channel MOSFET high-side switching |
| MOSFET | Vishay SUM70101EL-GE3 |
| Gate Control | Discrete BJT driver |
| PCB Configuration | 2 layers, 200 × 100 mm |
| Design Software | KiCad 9 |

### Engineering Focus

- Design of high-current DC power distribution circuits.
- Implementation of discrete MOSFET switching architecture.
- High-current PCB routing and copper-zone design.
- Component selection based on electrical requirements.
- Connector placement and power/ground layout.
- Thermal management considerations and via stitching.

### Development Status

**Design-stage project:** Initial PCB layout and routing have been completed. Formal electrical verification, fabrication, thermal validation, and hardware testing are not yet documented.

The published specifications represent design objectives rather than verified hardware ratings.

### Tools and Technologies

KiCad 9, Power Electronics, PCB Layout, MOSFET Switching, DC Power Distribution, and Robotics Electrical Systems.
