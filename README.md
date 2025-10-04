# FHDO LogiBox - Logic Gate Demonstrator

## Project Overview

This open-source hardware project is a 10x10 cm PCB designed to demonstrate the function of seven fundamental logic gates: OR, AND, NAND, NOR, XOR, XNOR, and NOT. The board uses three standard logic ICs (quad NAND, quad XOR, octal inverter) and lets users manually set two logic inputs (A and B) using physical switches. The output (Y) is shown via an LED, so you can instantly see the result for every gate type. Both input states (A and B) are likewise visualized with LEDs for clear feedback.

This demonstrator is well suited for classrooms, workshops, and self-guided learning, offering a practical way to investigate digital logic functions. It also serves as an accessible soldering project, with through-hole switches and ICs providing a straightforward assembly experience for beginners.

## Features
+ Demonstrates 7 logic gates using real hardware.
+ Inputs A and B set by physical switches; outputs displayed with LEDs.
+ Powered by a single cell LiPo battery, rechargable via USB-C.
+ Battery management on-board (overcharge, over-discharge protection etc.).
+ All design files and documentation provided for easy replication.

## Ordering and Manufacturing Guide
### Ordering the PCB:
+ Download the Gerber files from the repository.
+ Upload them directly to a PCB manufacturer such as JLCPCB, PCBWay, or Aisler.
+ Use the provided BOM for easy component sourcing.

### SMD Assembly:
+ You may opt for SMD components to be pre-soldered by the manufacturer (for example, JLCPCB offers assembly service with parts specified in the BOM).
+ If assembling multiple boards yourself, it is highly recommended to order a solder paste stencil to simplify SMD placement.
+ The board can be assembled manually with basic soldering tools. Use the KiCad schematic and layout for guidance during assembly.

### Enclosure:
+ Print the enclosure parts from the Enclosure folder using a 3D printer and follow the assembly guide included in the documentation.

### Usage:
+ Power up the device with the main switch.
+ Select the desired logic gate and toggle inputs A and B via switches; observe the results on the Y LED.
