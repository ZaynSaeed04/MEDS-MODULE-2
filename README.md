# MEDS Lab — Module 2: SystemVerilog for Digital Design

This repository contains design source files, testbenches, and lab documentation for **Module 2**, covering digital system design fundamentals using SystemVerilog. 
---

## 📁 Project Structure
**Task 5: Self-Checking Testbenches & Exhaustive Loop Testing**, featuring combinational gate modeling, automated self-checking tasks, and exhaustive verification loops.

```text
.
├── rtl/
│   ├── and_gate.sv       # Basic AND gate design module
│   └── 3gates.sv         # Multi-gate design module (AND, OR, XOR)
├── tb/
│   ├── tb_and_gate.sv    # Basic initial testbench for AND gate
│   ├── tb_and_gate_sc.sv # Self-checking testbench for AND gate
│   ├── tb_and_gate_sf.sv # Self-checking testbench with expected_fn
│   └── tb_3gates.sv      # Exhaustive loop-based testbench for all 3 gates
├── Reports/
│   └── T5.pdf            # Report (Task 5)
├── .gitignore            # Ignored build and simulation artifacts
└── README.md             # Project documentation