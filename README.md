# Federated Energy-Efficient Cloud Allocation

## Overview
A simulation framework for energy-efficient resource allocation in cloud data centers using Federated Learning. This project addresses the challenge of optimizing power consumption while maintaining privacy across distributed cloud nodes.

## Features
-   **Federated Learning**: De-centralized model training on local node data.
-   **Energy Optimization**: Algorithms to minimize active server count.
-   **Privacy Preservation**: Raw usage data never leaves the local node.
-   **Simulation**: extensible environment to test various allocation policies.

## Technology Stack
-   **Simulation**: CloudSim / Custom Python Simulator.
-   **ML**: PyTorch / TensorFlow Federated.
-   **Language**: Python / Java.

## Usage Flow
1.  **Initialize**: Setup cloud nodes with random workload distributions.
2.  **Train**: Local models learn usage patterns on each node.
3.  **Aggregated**: Global model updates weights without sharing data.
4.  **Allocate**: Optimized policy distributes VMs to minimize energy.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/Federated-Cloud-Allocation.git

# Run simulation
python simulate.py --nodes 10 --epochs 50
```

## License
MIT License

## Author
**Karthik Idikuda**
