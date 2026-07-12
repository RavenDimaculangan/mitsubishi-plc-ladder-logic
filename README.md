# Industrial Mitsubishi PLC Architecture & Ladder Logic Implementations

## Project Overview
This repository serves as a centralized portfolio for my core industrial automation code architectures written for **Mitsubishi Programmable Logic Controllers (PLCs)**. 

Using **Mitsubishi GX Works**, I design, simulate, and debug operational technology (OT) applications. This codebase focuses on industrial scan cycle optimization, sequential state-machines, bit-shifting matrices, and absolute interlocking safety rungs.


## Key Engineering Skills Demonstrated
* **Industrial Scan Cycle Optimization:** Structuring Ladder Logic to execute efficiently within traditional cyclic controller execution bounds.
* **Hardware Interlocking & Safety Cells:** Programming cascading timer sequences, conditional latching logic, and fail-safe master control relays to govern automated processes safely.
* **Data Registers & Timer Arrays:** Utilizing `D` (Data) registers and `T` (Timer) bits to map out state transitions and architectural logic tracking.


## Technical Stack
* **PLC Programming Environments:** Mitsubishi GX Works2 / GX Works3
* **Languages Standardized:** Ladder Diagram (LD)
* **Target Hardware Architectures:** Mitsubishi FX-Series / Q-Series Frameworks


## Automation Project Index
### 1. Parking Gate Infrastructure Control System (`/Parking-Gate-Control/`)
* **Logic Framework:** Utilizes sensor-latching registers to detect vehicle arrival, drives directional timers to safely actuate gate arms, and integrates counter logic to track total vehicle occupancy while activating warning lights.

### 2. Sequential Time-Based Lighting Matrix (`/Eiffel-Tower-Sequencer/`)
* **Logic Framework:** Built heavily upon cascading timer arrays and comparative data logic. Uses precise pointer flags to smoothly transition across distinct lighting states, flicker routines, and synchronized strobe patterns simulating architectural lighting shows.

### 3. Automated Production Line Conveyors (`/Conveyor-Process-Logic/`)
* **Logic Framework:** Integrates physical start/stop station loops with internal master control relays, utilizing proximity photoelectric sensor bits to automatically flag, index, and move packages across independent motor zones safely.

### 4. Advanced Laboratory Automation Logic (`/Core-Lab-Benchmarks/`)
* **Logic Framework:** A compilation of core laboratory benchmarks verifying basic and intermediate PLC capabilities, covering Boolean rungs, mathematical scaling, and bit-shifting operations.
