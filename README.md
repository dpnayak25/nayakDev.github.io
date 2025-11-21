# 🧠 Computational Fluid Dynamics (CFD) Research Portfolio  
A dedicated space to showcase my research work in **bio-inspired propulsion**, **fluid–structure interaction**, and **numerical methods in CFD** using **OpenFOAM**, **MATLAB**, and **ParaView** on both **local & HPC systems**.

---

## 🚀 Quick Navigation  
[![Home](assets/home.svg)](./README.md)
[![Research](assets/research.svg)](./research.md)
[![Animations](assets/animations.svg)](./animations.md)
[![About Me](assets/aboutMe.svg)](./aboutMe.md)
[![Google Scholar](assets/scholar.svg)](https://scholar.google.com/citations?user=hAG54CMAAAAJ&hl=en&oi=ao)
[![Contact](assets/contact.svg)](./contact.md)

---

## 🔬 Research Focus

**Primary Topics**  
✔ Fluid–Structure Interaction (FSI)  
✔ Overset Mesh & SixDoF Motion (OpenFOAM)  
✔ Carangiform & Flapping-Based Propulsion  
✔ Vortex Dynamics (2D & 3D)  
✔ Nonlinear Spring Models (Duffing-type)  
✔ Energy Extraction via Flutter Phenomena  
✔ MATLAB-based FFT / Cycle Extraction Scripts  

**Software & Tools**  
| Tool | Use Case |
|------|----------|
| OpenFOAM | Simulations & Custom Solvers |
| MATLAB | Data Processing & FFT |
| ParaView / Tecplot | Flow Visualization |
| C++ | Solver Modifications |
| Bash / WSL | Automating OpenFOAM Pipelines |
| HPC Systems | Slurm, Job Scripts, Scaling |

---

## 📌 Current Work

I am modeling **a carangiform swimmer** where the **body has prescribed undulation**, while the **tail undergoes passive flow-induced pitching** using a **torsional spring-damper model**.

| Parameter | Purpose |
|-----------|---------|
| Re = 500 / 5000 | Small vs. Large Swimmer |
| J\* | Controls added inertia |
| ζ | Damping ratio at peduncle |
| f\* | Reduced frequency |
| Solver | `dynamicOversetFvMesh` + `sixDoFRigidBodyMotion` |

🔓 Objective:  
➡ Understand how **nonlinear stiffness** affects thrust + power ratio  
➡ Compare **active vs. passive pitching** under different flow regimes  
➡ Visualize **vortex breakdown & LEV / TEV development**

---

## 🎬 Simulation Animations & Flow Visuals
➡ **See full gallery in** 👉 [`animations.md`](./animations.md)

| Visual | Description |
|--------|-------------|
| LEV Formation | High-angle dynamic stall |
| Ring Vortex | 3D flow structure |
| Streamwise Wake | Thrust-producing structures |
| Poincaré Maps | Limit-cycle extraction |


---

## 🧰 Key MATLAB Scripts (Data Processing)

| Script | Purpose |
|-------|--------|
| `extractAngle_fullWave.m` | Extract pitch angle over time |
| `extractForces_last10.m` | Steady-state force analysis |
| `extractFFT_spectrum.m` | Dominant frequency detection |
| `extractPoincarePoints.m` | Poincaré mapping of cycles |

---

## 🧾 Education

| Degree | Institute | Year |
|--------|-----------|------|
| MSc. Mechanical Engineering | Lakehead University | 2025 |
| BSc. Mechanical Engineering | Lakehead University | 2022 |

---

## 📩 Contact

| Method | Details |
|--------|--------|
| Email | dpnayak@lakeheadu.ca |
| LinkedIn | https://www.linkedin.com/in/dev-nayak |
| Google Scholar | https://scholar.google.com/citations?user=hAG54CMAAAAJ&hl=en&oi=ao |

---

### 🧬 *This portfolio is continuously evolving — just like fluid flow.*
