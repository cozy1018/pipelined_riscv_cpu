# Pipelined RISC-V CPU

A 5-stage pipelined RV32I RISC-V CPU core implemented in SystemVerilog.  
Supports basic forwarding, stalling, and memory access.  
Designed for integration with AXI4-Lite peripherals.

## Pipeline Stages

- IF: Instruction Fetch
- ID: Instruction Decode & Register Fetch
- EX: Execute (ALU + Branch)
- MEM: Memory Access
- WB: Write Back

## Features
- RV32I Base Integer ISA
- 5-stage Pipeline
- Hazard Detection Unit
- Data Forwarding
- Stalling Logic
- AXI4-Lite Master for I/O

## Testbenches
- Simulation via Icarus Verilog
- Example programs in assembly