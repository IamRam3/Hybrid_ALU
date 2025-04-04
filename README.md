# Hybrid Arithmetic Logic Unit (ALU) in 65nm Technology

## Overview

This project focuses on designing and analyzing two different 4-bit Hybrid Arithmetic Logic Units (ALUs) using 65nm technology. The primary objective is to optimize power consumption and delay while maintaining efficient arithmetic and logical operations.

## Outcomes & Achievements

- **Achieved** a **50% reduction** in power consumption by implementing efficient **low-power design techniques.**

- **Enhanced computational speed** by **5.21%** by **reducing propagation delay** from 1114ps to 1056ps using hybrid logic integration.

- Successfully implemented two Hybrid ALUs using Cadence Virtuoso, **integrated CMOS, PTL, and TG technologies.**

- **Validated performance improvements** through detailed simulations and analysis.

- **Optimized power-delay product (PDP) by 41.4%,** reducing it from 44.37 × 10⁻²⁰ to 26 × 10⁻²⁰. Demonstrating superior efficiency over traditional ALUs.

## Abstract

The Arithmetic Logic Unit (ALU) is a fundamental component of the CPU that executes arithmetic and logic operations. This project presents a comparative analysis of different ALU designs based on CMOS, Pass Transistor Logic (PTL), and Transmission Gate (TG) techniques. The study aims to improve performance by reducing power consumption and delay.

## Introduction

A 4-bit ALU is designed using different logic design methodologies. The design includes:

1. **Arithmetic Unit** - Performs basic arithmetic operations like addition and subtraction.

2. **Logical Unit** - Handles Boolean operations such as AND, OR, XOR, and NOT.

## ALU Design

### 1-Bit ALU

The fundamental building block for the 4-bit ALU is a 1-bit ALU, designed using different logic styles.

### 4-Bit ALU Architectures

- **CMOS-based ALU**

- **Pass Transistor Logic (PTL) ALU**

- **Transmission Gate (TG) ALU**

### Proposed Hybrid ALUs

Two hybrid ALU architectures are proposed:

1. **Low Power 4-bit Hybrid ALU:** Optimized for power efficiency.

2. **High Performance 4-bit Hybrid ALU:** Optimized for speed.

### Comparison and Results

The designed ALUs are evaluated in terms of:

- **Power Consumption**

- **Propagation Delay**

- **Power-Delay Product (PDP)**

### Conclusion

The proposed hybrid ALUs demonstrate significant improvements in either power consumption or delay compared to traditional designs.

### Future Scope

Further research can focus on:

- Extending the design to 8-bit and 16-bit ALUs.

- Implementing the design in FPGA and ASIC for real-world applications.

- Exploring FinFET technology for better efficiency.

### Repository Structure

~~~
├── docs/             # Documentation and reports
├── src/              # HDL (VHDL/Verilog) source code
├── simulations/      # Simulation results and testbenches
├── images/           # Block diagrams and schematics
└── README.md         # Project documentation
~~~

### How to Run Simulations

see the README.md file inside the simulations directory.

### To-Do:

- [x] Create Structure.
- [x] Add readme.
- [ ] Upload the files.
- [ ] Upload the book also.



