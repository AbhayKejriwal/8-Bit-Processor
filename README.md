
# Basic 8-Bit Processor with Verilog

This project is an implementation of a simple 8-bit processor in Verilog. It includes two main components: the `Basic8BitProcessor` module, which represents the processor, and the corresponding testbench for verification.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running the Testbench](#running-the-testbench)
- [Processor Functionality](#processor-functionality)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project consists of two key components:

- **Basic8BitProcessor**: This Verilog module represents a simple 8-bit processor with an accumulator, an ALU (Arithmetic Logic Unit), and memory. It is designed to execute a set of basic instructions.

- **Testbench**: The testbench is used to simulate the behavior of the processor and verify its functionality. It provides a sequence of instructions and checks the expected results.

## Getting Started

### Prerequisites

To work with this project, you will need:

- A Verilog simulator (e.g., ModelSim, XSIM).

### Running the Testbench

1. Clone the repository to your local machine.
2. Open your Verilog simulator and load the project files, including `Basic8BitProcessor.v` and `Basic8BitProcessorTestbench.v`.
3. Run the simulation, following the guidelines for your specific simulator.

The testbench will execute a sequence of instructions and check the behavior of the processor.

## Processor Functionality

The `Basic8BitProcessor` module implements a simple processor with the following instructions:

- **LDI (Load Immediate)**: Load an immediate value into the accumulator.
- **ST (Store)**: Store the value in the accumulator to memory.
- **ADDI (Add Immediate)**: Add an immediate value to the accumulator.
- **SUBD (Subtract Direct)**: Subtract a value from memory at a specified address from the accumulator.

The processor executes these instructions and updates the accumulator and memory accordingly.

## Contributing

Contributions to this project are welcome! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
