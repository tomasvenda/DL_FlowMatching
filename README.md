# Conditional Flow Matching, PINNs, and DeepONets for Phase-Field Modeling

**Course:** 02456 Deep Learning, DTU Compute (Fall 2025)  
**Authors:**  
- Diogo Cardoso (s253521)
- Andrei Farcas (s242999)
- Tomas Venda (s243028)
- Samuel Tavares (s251921)

---

## Project Overview

Phase-field models, such as the **Allen-Cahn equation**, are essential for simulating interfacial dynamics in materials science. However, resolving sharp phase boundaries (controlled by the parameter $\epsilon$) is computationally expensive for traditional numerical solvers.

In this project, we propose a generative approach using **Optimal Transport Conditional Flow Matching (OT-CFM)**. Unlike optimization-based Physics-Informed Neural Networks (PINNs), our method learns a time-dependent vector field that efficiently transports a noise distribution to the target distribution of PDE solutions.
