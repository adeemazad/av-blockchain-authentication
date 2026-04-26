# HB-RPVAM: Hybrid Blockchain Authentication for Autonomous Vehicle Communication

A secure vehicle-to-vehicle (V2V) communication system implementing a 
Hybrid Reputation-Based blockchain authentication model with neural 
network anomaly detection, built using Hyperledger Fabric and LabVIEW.

## Overview

Modern autonomous vehicle networks face critical security challenges 
in authenticating communication between vehicles in real time. 
Off-the-shelf solutions introduce unacceptable latency or fail to 
scale across large vehicle networks.

This project designs, implements, and validates a novel Hybrid 
Reputation-Based Vehicle Authentication Model (HB-RPVAM) that 
combines blockchain-based trust management with neural network anomaly 
detection to secure V2V communication at scale.

## Key Results

- 3x lower authentication latency compared to baseline models
- 85% reduction in blockchain transaction costs
- O(log n) authentication scalability validated across simulations 
  of 100 to 1,000 vehicles
- Real-time threat identification through neural network anomaly detection

## System Architecture

The system integrates three core components:

- **Hyperledger Fabric** — permissioned blockchain network managing 
  vehicle identity and reputation scores
- **Neural Network Anomaly Detection** — real-time identification of 
  malicious or compromised nodes within the vehicle network
- **LabVIEW Simulation Environment** — validated performance across 
  variable network sizes and traffic conditions

## Technologies Used

- Hyperledger Fabric
- LabVIEW
- Python
- Cryptographic authentication protocols
- Neural network-based anomaly detection

## Repository Contents

| File | Description |
|------|-------------|
| HB-RPVAM.pdf | Full dissertation and technical report |
| Presentation.pptx | Project presentation slides |
| Cryptographic Authentication.jpeg | System architecture diagram |
| Cryptographic Authentication.mp4 | Live demonstration video |
| Authentication Latency.svg | Performance graph — latency results |
| Bandwidth Consumption.svg | Performance graph — bandwidth results |
| Communication Overhead Reduction.svg | Performance graph — overhead results |
| Crypto.llb | LabVIEW library file |
| Large Numbers.llb | LabVIEW library file |

## Note on Source Code

This project was developed using university-licensed Hyperledger Fabric 
infrastructure and LabVIEW software. Source code is not available for 
public redistribution. Full technical documentation, performance results, 
system architecture diagrams, and a live demonstration video are included 
in this repository.

## Author

**Adeem Azad**  
BEng Mechatronics, University of Glasgow   
[LinkedIn](https://www.linkedin.com/in/adeem-azad)
