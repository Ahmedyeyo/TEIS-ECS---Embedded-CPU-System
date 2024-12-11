# TEIS ECS - Embedded CPU System

An advanced FPGA-based CPU architecture for real-world embedded system applications.

## Project Overview
This project involves the design, simulation, and hardware implementation of a CPU system on an FPGA. The CPU is supported by components like ROM, address decoders, input filters, and displays. The design showcases a full digital design cycle from VHDL coding to hardware validation.

Key features include:
1. **CPU Design**: A simple, robust CPU with fetch, decode, execute, and store stages.
2. **Memory Integration**: ROM for instruction storage and registers for execution.
3. **Peripheral Management**: Seven-segment displays for real-time status monitoring.
4. **Hardware Validation**: Integration with ISSP for signal observation and system validation.

## Features
- **Full CPU Workflow**: Instruction decoding, memory access, and data manipulation.
- **Real-Time Monitoring**: ISSP probes for observing critical signals like reset, PC, and CPU state.
- **Validation Framework**: Comprehensive ModelSim simulations and hardware validations.

## File Structure
- **src/**: VHDL source files for all system components.
- **doc/**: Technical documentation, including design specifications and simulation results.
- **simulation/**: ModelSim do-files, testbenches, and waveforms.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/TEIS_ECS.git
