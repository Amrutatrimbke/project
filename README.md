# Monte Carlo Simulation for Barrier Option Pricing using OpenMPI

## Overview

This project implements a Monte Carlo simulation for pricing barrier options using OpenMPI for parallel computation. Barrier options are a type of exotic option where the payoff depends on whether the underlying asset's price reaches a certain barrier level during the life of the option.

The purpose of this project is to demonstrate the use of parallel computing techniques to efficiently price barrier options by leveraging multiple processors to handle large-scale simulations.

## Features

- **Monte Carlo Simulation**: Uses random sampling to estimate the price of barrier options.
- **Barrier Option Pricing**: Supports various types of barrier options including up-and-out, down-and-out, up-and-in, and down-and-in.
- **Parallel Computation**: Utilizes OpenMPI to distribute the simulation workload across multiple processors, significantly reducing computation time.

## Requirements

- **OpenMPI**: Ensure OpenMPI is installed on your system.
- **C/C++ Compiler**: Compatible with GCC or any standard C++ compiler.
- **Make**: For building the project (optional if using an alternative build system).

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/monte-carlo-barrier-options.git
   cd monte-carlo-barrier-options
