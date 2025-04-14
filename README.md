# CODTECH Internship Project  
## Synchronous RAM Module (Read/Write)

**Intern Name**: [Durgesh Kumar Nishad]  
**Internship Domain**: VLSI Design  
**Company**: CODTECH IT SOLUTIONS  
**Project**: Simple Synchronous RAM Module  
**Completion Date**: [20/4/2025]  

---

## Description

This project implements a simple **Synchronous RAM** in Verilog with support for **read and write operations** triggered by the clock's rising edge. The module is parameterized to support configurable data and address widths.

---

## Files Included

| File Name              | Description                                  |
|------------------------|----------------------------------------------|
| `synchronous_ram.v`    | Main Verilog module for synchronous RAM      |
| `tb_synchronous_ram.v` | Testbench for verifying RAM functionality    |
| `README.md`            | Project overview and instructions            |
| `simulation_log.txt`   | (Optional) Output from testbench simulation  |

---

## Features

- Synchronous operation on positive clock edge  
- Parameterized address and data width  
- Simple write and read access  
- Testbench with predefined scenarios

---

## How to Simulate

iverilog -o ram_test tb_synchronous_ram.v synchronous_ram.v
vvp ram_test

### Using Icarus Verilog:
```bash
iverilog -o ram_test tb_synchronous_ram.v synchronous_ram.v
vvp ram_test# RAM-DESIGN

