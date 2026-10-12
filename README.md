# QFF 2026 Hackathon - Quantum Optimization Track

## Problem Statement
- **Track:** Quantum Optimization
- **Problem Statement:** Max-Cut on a Graph (O1)

## Team Members
- N. Deepika

## Approach
We implemented a QAOA circuit for a graph and benchmarked its performance across Processor A (5-qubit line/branch topology) and Processor B (9-qubit heavy-hex topology) using Qiskit.

## Results & Architecture Comparison
- **Processor A:** Circuit Depth = 17, Required 1 SWAP operation due to limited linear connectivity.
- **Processor B:** Circuit Depth = 14, More efficient routing due to the heavy-hex architecture.