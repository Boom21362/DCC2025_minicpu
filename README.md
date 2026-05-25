# Mini-CPU Project: DCC2025

<div align="center">

![Logo](path-to-logo) <!-- TODO: Add project logo (e.g., a CPU schematic icon) -->

[![GitHub stars](https://img.shields.io/github/stars/Boom21362/DCC2025_minicpu?style=for-the-badge)](https://github.com/Boom21362/DCC2025_minicpu/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Boom21362/DCC2025_minicpu?style=for-the-badge)](https://github.com/Boom21362/DCC2025_minicpu/network)

**A foundational mini-CPU design implemented with a Digital Circuit Editor, accompanied by comprehensive technical documentation.**

</div>

## Overview

This repository presents the design and associated technical documentation for a simple mini-CPU, developed as part of the DCC2025 project. The CPU architecture is realized using a digital circuit editor, providing a hands-on example of fundamental computer organization principles. It serves as an educational resource for understanding basic CPU components, instruction execution, and digital logic implementation.

The project includes the complete circuit files for the CPU, along with detailed documentation covering its instruction set, architecture, and operational principles.

## Key Architectural Features

This mini-CPU embodies core components essential to a functional processor:

-   **Instruction Set Architecture (ISA):** A defined set of operations the CPU can perform.
-   **Program Counter (PC):** Manages instruction sequencing.
-   **Arithmetic Logic Unit (ALU):** Performs arithmetic and logical operations.
-   **Registers:** General-purpose and special-purpose registers for data storage and manipulation.
-   **Control Unit:** Decodes instructions and generates control signals for other components.
-   **Memory Interface:** For fetching instructions and data from memory.

## Technology & Tools

**Design Environment:**
-   **Digital Circuit Editor:** The CPU's logic is designed and simulated using a dedicated digital circuit editor (e.g., Logisim, Digital, etc.). Specific software not detected in codebase, generic placeholder used.

## Getting Started

To explore or run this mini-CPU design, you will need a compatible digital circuit editor.

### Prerequisites
-   A **Digital Circuit Editor** (e.g., Logisim Evolution, Digital, etc.) installed on your system.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Boom21362/DCC2025_minicpu.git
    cd DCC2025_minicpu
    ```

2.  **Open the project files**
    Navigate to the `project/` directory and open the main circuit file(s) (e.g., `.circ`, `.dig`, or similar format) using your digital circuit editor.

## Project Structure

```
DCC2025_minicpu/
├── README.md           # This README file
├── instruction/        # Directory containing technical documentation (e.g., ISA, architecture details)
└── project/            # Directory containing the actual digital circuit design files for the CPU
```

## Technical Documentation

The `instruction/` directory contains detailed technical documentation for the mini-CPU. This typically includes:

-   **Instruction Set Architecture (ISA):** A complete list of supported instructions, their opcodes, operands, and functionality.
-   **CPU Architecture Diagram:** Visual representation of the CPU's components and data paths.
-   **Component Descriptions:** Detailed explanations of the ALU, control unit, registers, and memory interface.
-   **Usage Guides:** Information on how to load and simulate programs on the CPU within the digital circuit editor.

Please refer to the files within the `instruction/` directory for in-depth understanding.

## Contributing

We welcome contributions to this project! If you have suggestions for improvements to the CPU design, documentation, or new features, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## Acknowledgments

-   Developed by **Chonchanok S., Jesadakorn N., Napat P., Thaweechai P.**

---
PS: This repository is part of the "2110252 Digital Computer Logic" course under the Department of Computer Engineering, Chulalongkorn University

