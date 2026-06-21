# VLSI Project 02 – FIFO Verification

## Overview

This project demonstrates the design and verification of a synchronous FIFO (First-In-First-Out) memory using Verilog HDL and SystemVerilog. The FIFO stores incoming data and retrieves it in the same order, ensuring data integrity during communication between digital systems.

## Objectives

- Design a FIFO using Verilog HDL
- Implement write and read operations
- Develop a SystemVerilog testbench
- Verify FIFO functionality through simulation
- Analyze waveforms and simulation results in Vivado

## Tools Used

- Vivado 2020.1
- Verilog HDL
- SystemVerilog
- XSim Simulator

## Project Files

```text
fifo.v       - FIFO RTL Design
fifo_tb.sv   - SystemVerilog Testbench
```

## FIFO Operation

### Write Sequence

```text
10
20
30
40
50
```

### Read Sequence

```text
10
20
30
40
50
```

## Simulation Results

```text
=== FIFO Verification Started ===

WRITE : 10
WRITE : 20
WRITE : 30
WRITE : 40
WRITE : 50

PASS : Expected=10 Received=10
PASS : Expected=20 Received=20
PASS : Expected=30 Received=30
PASS : Expected=40 Received=40
PASS : Expected=50 Received=50

=== Verification Completed ===
```

## Verification Flow

1. Apply Reset
2. Write Data into FIFO
3. Read Data from FIFO
4. Compare Expected and Received Data
5. Verify Data Integrity
6. Analyze Waveforms

## Key Learning Outcomes

- FIFO Architecture
- Verilog RTL Design
- SystemVerilog Testbench Development
- Functional Verification
- Simulation and Debugging
- Waveform Analysis

## Screenshots

- RTL Design
- Testbench Code
- Simulation Waveform
- PASS Logs
- Elaborated Design Schematic

## Future Enhancements

- Full Flag Implementation
- Empty Flag Implementation
- Parameterized FIFO Depth
- Scoreboard Verification
- Assertions (SVA)
- Functional Coverage

## Author

**Narasimha Lakkimsetty**

B.Tech Electronics & Communication Engineering (ECE)

VLSI & FPGA Learner | Embedded Systems Enthusiast | Co-Founder, TapeoutX
