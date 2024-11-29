# Quantum-Mechanics-RTL
Final Year Project: Quantum Mechanics of RTL Model for Digital Modules
# Quantum Mechanics of RTL Model for Basic Digital Module Realization

## Abstract
This project explores the application of Quantum Mechanics in RTL (Register Transfer Level) design to reconcile classical and quantum computing paradigms. By leveraging quantum phenomena such as superposition and entanglement, it aims to significantly expedite computational tasks, surpassing the limitations of classical computers.

## Table of Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Implementation](#implementation)
- [Results](#results)
- [Applications](#applications)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [How to Run](#how-to-run)
- [Contributors](#contributors)

## Introduction
The project integrates quantum mechanics into RTL modeling, pioneering digital module realization. It uses reversible logic to reduce power consumption and improve efficiency.

## Features
- Energy-efficient reversible binary square rooter.
- Reduction in gate count from 75 to 35.
- 20% improvement in power efficiency.

## System Architecture
![System Architecture](diagrams/system_architecture.png)

## Implementation
The project uses a non-restoring algorithm for binary square root calculation. The design was implemented using Verilog and simulated using Xilinx ISE.

## Results
- Timing Constraints: 1.158 ns delay.
- Device Utilization:
  - Slice LUTs: 14/41,000 (1%)
  - Fully used LUT-FF pairs: 12/18 (66%)
  - Bonded IOBs: 14/300 (4%)

## Applications
- Quantum computing.
- Digital signal processing.
- Statistical analysis and machine learning.

## Conclusion
The project successfully designed a Binary Square Root using SRG reversible logic and a non-restoring algorithm. The design is energy-efficient and reduces gate count significantly.

## Future Work
- Explore hardware implementation on quantum processors.
- Integrate with quantum software frameworks.
- Develop educational resources for RTL design in quantum computing.

## How to Run
1. Install Xilinx ISE 14.7.
2. Open the project file in Xilinx.
3. Run the simulation to verify the results.

## Contributors
- **P. Pavan Kumar** (20691A04F5)
- **C. Prasad Raju** (20691A04G3)
- **R. Ranadeep Reddy** (20691A04H1)
- **Guide**: Mr. V. Mustafa, M.Tech, (Ph.D)
