# Physics-Informed Neural Network for Capillary Flow

This repository contains research work from my **Research Internship at the School of Energy Science and Engineering, IIT Kharagpur (Apr ’24 – Nov ’24)** under the supervision of **Prof. Chirodeep Bakli**.  
The project focuses on modelling **capillary-driven fluid flow** using **Physics-Informed Neural Networks (PINNs)**, combining experimental insights with governing equations in fluid mechanics.

---

## Overview
Capillary flow plays a crucial role in fluid dynamics and has traditionally been studied through **experimental methods**. While data-driven approaches can model these flows, they often lack physical consistency.  
**PINNs** offer a solution by embedding **physics-based constraints** into the learning process, allowing for accurate and interpretable models even when data is limited.

This project develops a PINN framework to simulate capillary flow and demonstrates the benefits of **physics-informed loss functions** compared to purely data-driven models.

---

## Key Contributions
- Conducted a **literature review** on physics-informed machine learning approaches for fluid mechanics.  
- Designed a **PINN architecture** for capillary flow problems, integrating experimental data with governing equations.  
- Engineered the **loss function** to incorporate residuals of physical laws, introducing a **learning bias** that enforces physical consistency.  
- Compared **baseline models** with **physics-informed models**, showing improved generalization and accuracy.  

---

## Methodology
1. **Problem Definition**: Modelling capillary rise phenomena, previously studied largely via experiments.  
2. **Model Design**: Developed a neural network with physics-constrained training objectives.  
3. **Loss Modification**: Combined experimental error terms with physics residuals.  
4. **Evaluation**: Benchmarked against experimental results to validate model performance.  

