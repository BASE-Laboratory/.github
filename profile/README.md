# BASE Laboratory
### Beamlines for Autonomous Science and Engineering

We are a joint research group between the **University of Greenwich** and the **Rutherford Appleton Laboratory (RAL)**. We build the software infrastructure to hardwire UK Exascale computing directly to Synchrotron beamlines.

<p align="center">
  <img src="https://github.com/BASE-Laboratory/.github/blob/main/assets/Heuristic_Control.png?raw=true" alt="ESME Framework Architecture" width="65%">
</p>

### ⚡ Research Focus
Our work targets the stochastic precursors to battery failure. We replace deterministic testing schedules with autonomous, AI-driven control loops that navigate the search space of material degradation in real-time.

* **Autonomous Control:** Reinforcement learning agents for active beamline steering (Diamond Light Source / ISIS).
    * *Theory:* Benchmarking Autonomy Taxonomy ([arXiv:2601.06978](https://arxiv.org/abs/2601.06978))
    * *Method:* The ESME Framework ([arXiv:2601.00851](https://arxiv.org/abs/2601.00851))
* **Generative Simulation:** Physics-informed diffusion models for surrogate modelling on GH200 hardware.
* **High-Throughput Physics:** Massively parallel transport solvers for terabyte-scale tomography.

<p align="center">
  <img src="https://github.com/BASE-Laboratory/.github/blob/main/assets/BASE_Scale.png?raw=true" alt="Levels of Autonomy Scale" width="60%">
</p>

### 📦 The Software & Data Stack
Our code is open-source and developed for Tier-1 National Supercomputing facilities (e.g. Isambard-AI).

| Repository | Domain | Description |
| :--- | :--- | :--- |
| [**OpenImpala**](https://github.com/BASE-Laboratory/OpenImpala) | ⚛️ Physics | Massively parallel solver for transport physics (AMReX/C++). (*SoftwareX* [2021](https://www.sciencedirect.com/science/article/pii/S2352711021000662)) |
| [**PorousDiff**](https://github.com/BASE-Laboratory/PorousDiff) | 🧠 GenAI | Conditional 3D diffusion for mechanical surrogate modelling. |
| [**LiionDB**](https://zenodo.org/records/5574514) | 🔋 Data | The community standard database for Li-ion battery parameters (Zenodo). |
| [**OpenLSR-X**](https://github.com/BASE-Laboratory/OpenLSR-X) | 👁️ Vision | SRGAN implementation for Synchrotron XCT super-resolution. |
| [**BatteryExplorer**](https://github.com/BASE-Laboratory/BatteryExplorer) | 📊 Viz | 4D interactive dashboard for operando failure analysis. |
| [**MultimodalBenchmark**](https://github.com/BASE-Laboratory/MultimodalBenchmark) | 💾 Data | Official code for the 3D Multimodal Synchrotron Dataset (*Sci. Data* [2025](https://www.nature.com/articles/s41597-025-04605-9)). |

### 📢 Opportunities
**PhD Studentship: Generative AI for Experimental Control**
We are recruiting a doctoral candidate to design the predictive engine for the "Self-Driving Microscope."
* **Focus:** Bayesian Optimization & Active Learning for X-ray Tomography.
* **Site:** Harwell Campus (RAL).
* **Contact:** James.LeHoux@greenwich.ac.uk

---
*© 2026 BASE Laboratory | Part of the M34Impact Institute*
