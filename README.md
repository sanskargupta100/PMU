# Optimal PMU Placement in Power Systems

This repository contains code and data for optimal Phasor Measurement Unit (PMU) placement to achieve full system observability with minimum deployment cost in power networks. [page:3]

## Overview

The PMU placement problem is formulated as an Integer Linear Programming (ILP) task, combined with a topology transformation technique that leverages Zero Injection Buses (ZIBs). [page:3] The approach introduces systematic merging rules for ZIBs to obtain exact and unambiguous PMU locations. [page:3]

## Key Features

- ILP-based formulation for optimal PMU placement. [page:3]  
- Topology transformation using Zero Injection Buses (ZIBs) and merging rules (Rule A, B, C). [page:3]  
- Validation on standard IEEE test systems (14-bus, 30-bus, 57-bus, 118-bus). [page:3]  
- Up to 50% reduction in required PMUs compared to naive placement. [page:3]  
- Hybrid ILP–Genetic Algorithm model implemented for the IEEE 30-bus system (PMUs reduced from 10 to 7 units). [page:3]

## Repository Structure

- `src/` – Main optimization and algorithm implementation. [page:3]  
- `data/` – IEEE test system data (bus, line, and measurement data). [page:3]  
- `results/` – Output files, placement configurations, and performance summaries. [page:3]  
- `docs/` – Supporting documentation, figures, and notes. [page:3]

(Adjust folder names above to match your actual structure.)

## Getting Started

1. Clone the repository. [page:3]  
2. Install required dependencies (e.g., Python packages, optimization solvers, or MATLAB toolboxes as applicable). [page:3]  
3. Run the main script or notebook for the desired IEEE test system. [page:3]

## Applications

This work is useful for researchers and engineers working on power system state estimation, wide-area monitoring, and smart grid planning where efficient PMU deployment is critical. [page:3]
