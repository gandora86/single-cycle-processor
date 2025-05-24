# 🚀 RISC V Based Single Cycle Processor

An RTL implementation of a **32-bit RISC-V Single Cycle Processor** in SystemVerilog, based on the textbook  
**_Digital Design and Computer Architecture: RISC-V Edition_** by **Sarah L. Harris** and **David Harris**.

---

## 📘 Reference

- **Book:** *Digital Design and Computer Architecture: RISC-V Edition*  
- **Authors:** Sarah L. Harris and David Harris

---

## ✅ Supported Instructions

| Type | Instructions Implemented |
|------|---------------------------|
| R    | ADD, SUB, SLT, SLTU, XOR, SRL, SRA, OR, AND |
| I    | LB, LH, LW, LBU, LHU, ADDI, SLTI, SLTIU, XORI, ORI, ANDI, SLLI, SRLI, SRAI |
| S    | SB, SH, SW |
| B    | BEQ |
| U    | LUI, AUIPC |
| J    | JAL |

> **Note:** 25 instructions implemented. Remaining: JALR, BNE, BLT, BGE, BLTU, BGEU

---

## 📁 Project Structure
├── LICENSE
├── README.md
├── rtl/
│ ├── ALU.v
│ ├── ALU_decoder.v
│ ├── ALU_Mux.v
│ ├── Control_Unit.v
│ ├── Core_Datapath.v
│ ├── Data_Memory.v
│ ├── Extend.v
│ ├── Instruction_Memory.v
│ ├── Main_Decoder.v
│ ├── PC.v
│ ├── PC_Mux.v
│ ├── PC_Plus_4.v
│ ├── PC_Target.v
│ ├── Register_File.v
│ ├── Result_Mux.v
│ ├── Single_Cycle_Core.v
│ └── Single_Cycle_Top.v
└── tb/
├── ALU_tb.v
├── ALU_Decoder_tb.v
├── ALU_Mux_tb.v
├── Control_Unit_tb.v
├── Core_Datapath_tb.v
├── Data_Memory_tb.v
├── Extend_tb.v
├── Instruction_Memory_tb.v
├── Main_Decoder_tb.v
├── PC_tb.v
├── PC_Mux_tb.v
├── PCPlus4_tb.v
├── PC_Target_tb.v
├── Register_File_tb.v
├── Register_tb.v
├── Result_Mux_tb.v
├── Single_Cycle_Core_tb.v
└── Single_Cycle_TB.v
---

## 🛠️ Features

- Fully synthesizable 32-bit single-cycle RISC-V processor
- Modular design with separate ALU, Control Unit, Datapath, and Memory
- Supports integer and immediate operations, loads/stores, branching, and jump
- Includes complete testbenches for individual modules and core integration

---

## 🧪 Simulation & Testing

Simulate using any SystemVerilog simulator like Vivado, VCS, ModelSim, or Xcelium. 

