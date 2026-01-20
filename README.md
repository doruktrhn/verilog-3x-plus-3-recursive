Recursive Verilog Design: Y = 3X + 3

This project implements the arithmetic function: Y = 3X + 3 with using recursive digital design techniques in Verilog.

Design Approach
- 1-bit Full Adder as base arithmetic unit
- N-bit Ripple Carry Adder built recursively using generate blocks
- Multiplication by 3 implemented as:
  - Left shift (2X)
  - Addition (2X + X)
- Constant addition (+3)

Verification
- Functional verification performed using Verilog testbench
- Simulation and waveform analysis via EPWave (EDAPlayground)

Expected Behavior
| X | Y |
| 0 | 3 |
| 1 | 6 |
| 2 | 9 |
| 3 | 12 |

Tools
- Verilog HDL
- Icarus Verilog
- EDAPlayground
