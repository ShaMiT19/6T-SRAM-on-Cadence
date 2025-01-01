# 4x2 SRAM Array Design Project

## Table of Contents
- [Project Overview](#project-overview)
- [Components](#components)
- [Design Process](#design-process)
- [Simulation Results](#simulation-results)
- [Team Members](#team-members)
- [Tools and Technology](#tools-and-technology)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Project Overview
This project focuses on the design, simulation, and layout development of a 4x2 Static Random Access Memory (SRAM) array using 45 nm process technology in the Cadence environment. The implementation integrates critical components, including row and column decoders, sense amplifiers, precharge circuits, and read-write logic.

### Key Features
- 4x2 SRAM array configuration
- 6-transistor SRAM bitcell design
- Integrated row and column decoders
- Sense amplifier for reliable data retrieval
- Precharge circuit for bitline preparation
- Comprehensive read and write circuitry

## Components
1. **Inverter**
   - Schematic, layout, and symbol designs
   - DRC and LVS validations

2. **3-Input NAND Gate**
   - Schematic, layout, and symbol designs
   - DRC and LVS validations

3. **SRAM Cell**
   - 6-transistor design
   - Schematic, layout, and symbol designs
   - DRC and LVS validations

4. **Row and Column Decoders**
   - 2x4 row decoder implementation
   - 1x2 column decoder implementation
   - Truth table and logic design

5. **Write Circuitry**
   - Detailed operation explanation for read and write processes

6. **Precharge Circuit**
   - Design for setting bitlines to the same voltage before read cycles

7. **Sense Amplifier**
   - Design for detecting and amplifying small voltage differences between bitlines

8. **Complete SRAM Array**
   - Integration of all components
   - Full schematic and layout designs

## Design Process
1. Component Design: Each component (inverter, NAND gate, SRAM cell, etc.) was individually designed, simulated, and validated.
2. Integration: Components were integrated to form the complete SRAM array.
3. Validation: Rigorous testing was performed at each stage, including DRC and LVS checks.
4. Simulation: Comprehensive simulations were conducted to verify functionality.

## Simulation Results
Detailed simulations were performed, including:
- Single SRAM Cell operation
- Writing and Reading '0' and '1' to the 8-bit SRAM Array
- Writing '11011011' Sequence to the SRAM Array

(Note: Specific simulation results and waveforms are not included in this README but were part of the project documentation.)

## Team Members
- Shamit Gajanan Savant
- Mohammed Faisal
- Vijaya Varshini Krishnaswamy
- Uthra Madhavan

## Tools and Technology
- Design Environment: Cadence Virtuoso
- Process Technology: 45 nm
- Simulation Tools: Cadence ADE (Analog Design Environment)
- Layout Tools: Cadence Virtuoso Layout Suite XL

## Installation and Setup
(Note: This section would typically include instructions for setting up the Cadence environment and importing the project files. As this is a university project, specific installation steps are not provided here.)

## Usage
To use this SRAM design:
1. Open the project in Cadence Virtuoso.
2. Navigate to the top-level schematic of the 4x2 SRAM array.
3. Run simulations using the provided testbenches.
4. View layouts and perform DRC/LVS checks as needed.

## Conclusion
The design, simulation, and layout of a 4x2 SRAM array were successfully completed using Cadence Virtuoso with a 45nm technology library. Each component was rigorously tested and verified. The layout design passed both Design Rule Check (DRC) and Layout Versus Schematic (LVS) validations without errors, demonstrating the project's success in creating a functional and reliable SRAM array design.
