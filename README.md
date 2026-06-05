# Gem5 Computer Architecture Project

## Program: Matrix Multiplication (4x4)
Simulation of matrix multiplication using Gem5 simulator with varying cache configurations.

## Experiments
| Config | L1D | L1I | L2 |
|--------|-----|-----|----|
| Baseline | 64kB | 64kB | 256kB |
| Small Cache | 32kB | 32kB | 128kB |
| Large Cache | 128kB | 128kB | 512kB |

## Repository Structure
- `matrix_mult.c` - Source code
- `matrix_mult` - Compiled static binary
- `results/` - Simulation statistics for each configuration

## How to Run
See report for detailed steps.
