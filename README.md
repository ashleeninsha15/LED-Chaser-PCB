# LED Chaser PCB

## Overview

This project is a 10-LED Chaser PCB designed using KiCad.

The circuit is based on:
- NE555 Timer IC
- CD4017 Decade Counter
- 10 LEDs
- Current limiting resistors

The NE555 operates in astable mode and generates clock pulses for the CD4017. The CD4017 sequentially activates one LED at a time, creating the LED chasing effect.

---

## Features

- Designed in KiCad 9
- Manual PCB routing
- Through-hole components
- Ground copper pour
- Gerber files ready for fabrication
- 3D PCB visualization

---

## Project Images

### Schematic

![Schematic](Images/Schematic.png)

### PCB Layout

![PCB Layout](Images/PCB_Layout.png)

### 3D View

![3D Front](Images/3D_Front.png)

![3D Angle](Images/3D_Angle.png)

---

## Repository Structure

```
LED-Chaser-PCB
├── KiCad
├── Gerber
├── Images
└── README.md
```

---

## Software Used

- KiCad 9
- GitHub

---

## Future Improvements

- Add ON/OFF switch
- Add power indicator LED
- Convert to SMD version
- Design a compact PCB

---

## Author

Ashleenin Shamma
ECE Student | PCB Design | Embedded Systems | VLSI Enthusiast
