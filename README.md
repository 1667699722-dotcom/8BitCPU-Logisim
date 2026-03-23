# 8BitCPU-Logisim
A complete implementation of an 8-bit CPU built entirely with Logisim Evolution, designed for students and hobbyists learning computer architecture.

## Project Overview
This project implements a fully functional 8-bit RISC CPU from scratch, based on the core theoretical framework of the classic book But How Do It Know? - The Basic Principles of Computers for Everyone.Focusing on the practical realization of fundamental computer architecture principles, the project reproduces the complete working mechanism of an 8-bit CPU, including instruction fetch, decode, execute, memory access, and write-back stages through hardware logic design, instruction set definition, and circuit simulation or physical implementation. Unlike abstract theoretical models, this implementation is interactive—you can simulate instruction execution, trace signal flow, and modify components to observe behavioral changes in real time.

## Core Features
- **8-bit Architecture**: 8-bit data path, 8-bit address bus (supports up to 256 bytes of memory addressing)
- **Functional Units**:
  - Arithmetic Logic Unit (ALU) supporting ADD, SUB, AND, OR, NOT operations
  - Program Counter (PC) and Instruction Register (IR) for instruction cycle management
  - 8 general-purpose 8-bit registers (R0-R7)
  - Control Unit with hardwired logic for instruction decoding
- **Instruction Set**: 16 basic instructions covering data movement, arithmetic, logic, and control flow
- **Simulation Ready**: Pre-configured test benches to validate CPU functionality
- **Educational Focus**: Well-commented circuit structure with clear component labeling for easy learning

## Requirements
- Logisim Evolution (v3.7.2 or later)
- Basic understanding of digital logic and CPU fundamentals

## How to Use
1. Download the `.circ` file from the repository
2. Open it in Logisim Evolution
3. Load the test program (included in `/test` directory)
4. Run the simulation to observe instruction execution

## Educational Value
This project is ideal for:
- Students studying computer organization/architecture
- Hobbyists exploring digital logic design
- Teachers creating hands-on lab exercises for CPU design
