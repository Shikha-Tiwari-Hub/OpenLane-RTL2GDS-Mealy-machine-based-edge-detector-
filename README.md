## OpenLane-RTL2GDS-Mealy-machine-based-edge-detector-

## Project Overview
This repository demonstrates how to implement a Mealy Machine-based Edge Detector and run it through the complete OpenLane RTL-to-GDSII flow. The design is written in Verilog, synthesized using Yosys, and taken through floorplanning, placement, clock tree synthesis, routing, and signoff to generate a final GDSII layout.

## Prerequisites
Before running your first design, ensure you have:
1. Completed the OpenLane installation as described in [Installation](https://deepwiki.com/The-OpenROAD-Project/OpenLane/2.1-installation)
2. A working Docker (or compatible container engine) installation

## Table of Contents
## Overview of OpenLane:
OpenLane is an open-source RTL-to-GDS (Register-Transfer Level to Graphic Data System) flow toolchain.\
It takes your Verilog RTL code and generates the final chip layout (GDSII) ready for fabrication.\
**Why OpenLane is used?**
- It allows anyone to do ASIC design with open-source tools.
- Works with SkyWater 130nm PDK.
- Provides a push-button flow (full automation) as well as step-by-step control for learning/debugging.
- Used in Google/Efabless shuttle programs for making real chips.

 ![WhatsApp Image 2025-08-26 at 15 10 30_00a1b3ac](https://github.com/user-attachments/assets/7df035aa-b2f9-4464-8d2c-9202ffc9c79c)


  ## Step-by-Step Commands
  

