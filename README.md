# CPU Test

This repository contains a set of digital-logic circuit designs for a simple 8-bit computer / CPU experiment. The project is implemented as `.dig` files, which are schematic files used by the Digital circuit simulator.

## Overview

The circuit designs in this repository model a bit-level processor-style datapath using standard logic primitives such as:

- AND / OR / XOR gates
- NAND-based logic
- NOT gates
- full-adder blocks
- flip-flops / state elements
- register-like and control-path structures

The main purpose appears to be exploration and testing of digital logic design for a small CPU architecture rather than a conventional software project.

## Repository contents

- `8bitPC.dig` — the primary 8-bit processor / computer circuit schematic
- `8bitPC_32_64.dig` — a larger variant of the design, likely intended for wider-bit experimentation or alternate configurations
- `.gitattributes` — repository normalization settings

## How to use

1. Install the Digital circuit simulator.
2. Open one of the `.dig` files from this repository.
3. Inspect or simulate the logic network.
4. Use the schematic as a reference for digital design experiments or learning.

## Notes

- This repository is best understood as a circuit-design prototype rather than a software application.
- There are no automated build or test scripts in the current repository.
- The designs are educational and exploratory in nature.

## License

No explicit license file is present in the repository, so the project should be treated as unlicensed unless otherwise stated by the repository owner.
