# Electric Press Automation System

Industrial automation and electrical redesign of a multi-line aluminum can press system.

---

## Overview

This project consists of the redesign, automation and electrical reengineering of an industrial electric press system used for aluminum can compaction.

### Main objectives

- Replace stepper motors with universal motors
- Redesign the complete electrical installation
- Implement PLC-based automation logic
- Correct power factor to 0.95 per production line
- Redesign motor protection and starting strategy
- Perform mechanical and electrical calculations

The system integrates mechanical transmission, electrical power circuits, PLC control logic and industrial safety measures.

---

## System Description

The automated production line includes:

- Can dispensing gate
- Weighing system
- Conveyor belts
- Electric press with pressure feedback
- Cube displacement mechanism
- Centralized protection and control panel

The press operates in three compression cycles to produce 100 kg aluminum cubes.

---

## Technical Highlights

### Mechanical Engineering

- Torque and speed recalculation for motor replacement
- Gear reduction selection for required output torque
- Mechanical load analysis
- Transmission verification

### Electrical Engineering

- Cable section calculation (ITC-BT-19)
- Protection device selection (MCB, RCD, thermal relays)
- Peak current analysis
- Capacitor bank sizing for power factor correction (cos φ = 0.95)

### Control System

- PLC-based automation (FBD logic)
- Pressure-based stroke limitation
- Timed motor start sequence
- Controlled activation of thermal relay and capacitor bank
- Multi-cycle compression control

---

## Repository Structure

- `docs/` → Technical documentation and budget  
- `analysis/` → Mechanical and electrical calculations  
- `electrical/` → Schematics and wiring diagrams  
- `plc/` → Control logic diagrams (FBD)  
- `cad/` → 3D system model  
- `docs/preliminary/` → Initial design study  

---

## Tools Used

- SolidWorks Electrical
- PLC programming (FBD)
- Industrial motor sizing tools
- Low voltage electrical regulation (REBT)

---

## Engineering Scope

- Industrial automation
- Electrical installation redesign
- Power factor correction
- Mechanical transmission design
- Risk assessment and safety planning
