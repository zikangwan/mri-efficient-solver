# mri-efficient-solver
Efficient nonlinear dynamic analysis software for metal rubber isolation systems

## About
This repository hosts the source code of the dedicated rapid analysis software presented in the paper:  
**Efficient Nonlinear Dynamic Analysis Method of Metal Rubber Isolation Systems: Algorithm and Software**

> **Status Notice**  
> This is the source code package accompanying the submitted manuscript. The repository is currently in pre-release status. The complete source code, full documentation and usage examples will be officially released and made fully publicly available once the paper is accepted for publication.

## Core Methodology
The software implements a two-step time-domain least-squares equivalent linearization method for hysteretic nonlinear systems, coupled with Newton-Raphson iteration for direct computation of system resonance peaks. It achieves approximately 480× computational speedup relative to the alternating frequency/time (AFT) harmonic balance method, with a maximum error of 1.46% in resonant frequency prediction.

## Main Features
- Sequential identification of equivalent stiffness and damping via two-step least-squares fitting
- Direct solving of resonant frequency and peak acceleration transmissibility
- Parametric uncertainty quantification based on Latin hypercube sampling
- Graphical user interface built with PyQt5
- Built-in parameter library for 5 types of metal rubber isolators
- Result visualization and Excel data export

## Citation
If you use this code in your research, please cite the corresponding paper. Full citation information will be updated upon publication of the manuscript.
