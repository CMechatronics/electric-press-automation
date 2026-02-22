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

## Key Technical Specifications

| Parameter | Value |
|------------|--------|
| System Type | Industrial Electric Press |
| Production Configuration | Multi-line automated system |
| Supply Voltage | 400 V – Three-phase |
| Press Motor Power | 37 kW |
| Press Rated Speed | 1480 rpm |
| Gear Reduction Ratio | 3:1 |
| Output Torque (Press Shaft) | 717 Nm |
| Compression Force (per cycle) | 980 N |
| Conveyor Motor Power | 0.37 kW |
| Actuator Motor Power | 4 kW |
| Power Factor Target | cos φ = 0.95 (per line) |
| Control System | PLC (FBD Logic) |
| Compression Cycles | 3 per production cycle |
| Final Product | 100 kg aluminum cube |

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

- Motor replacement and torque adaptation through gearbox selection
- Output torque verification (717 Nm)
- Mechanical transmission ratio calculation (3:1)
- Load and shaft analysis

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
- Industrial motor sizing methodology
- Low voltage electrical regulation (REBT)

---

## Engineering Scope

- Industrial automation
- Electrical installation redesign
- Power factor correction
- Mechanical transmission design
- Risk assessment and safety planning
