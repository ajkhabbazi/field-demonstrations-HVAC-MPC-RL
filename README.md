# Field Demonstrations of MPC and RL for HVAC

**Lessons learned from field demonstrations of model predictive control and reinforcement learning for residential and commercial HVAC: A review**

*Applied Energy, 399, 126459 (2025)*

Arash J. Khabbazi · Elias N. Pergantis · Levi D. Reyes Premer · Panagiotis Papageorgiou · Alex H. Lee · James E. Braun · Gregor P. Henze · Kevin J. Kircher

[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.apenergy.2025.126459-blue)](https://doi.org/10.1016/j.apenergy.2025.126459)

---

![Field Demonstrations of MPC and RL for HVAC](field-demonstrations-HVAC-MPC-RL.gif)

---

## Overview

Heating, ventilation, and air conditioning (HVAC) systems account for roughly 15% of global greenhouse gas emissions and cost on the order of $1 trillion per year in energy bills. Model predictive control (MPC) and reinforcement learning (RL) have shown strong promise in simulation — yet neither has seen widespread deployment in real buildings.

This paper provides the **most comprehensive review to date** of peer-reviewed field demonstrations of MPC and RL for residential and commercial HVAC, analyzing 104 papers that collectively report 206 field tests. Beyond summarizing existing work, the paper critically evaluates experiment protocols used in past studies and provides concrete, actionable guidance for future field research.

---

## Key Highlights

- **Scope of the review.** We identified and analyzed all known peer-reviewed field demonstrations of MPC and RL for HVAC published between 1997 and 2025 — 24 residential papers (52 tests) and 80 commercial papers (154 tests) across multiple continents and climate zones.

- **Field research remains rare.** Despite thousands of simulation studies, field demonstrations account for only ~4% of all MPC and RL publications. Addressing this gap is essential for accelerating real-world adoption.

- **Experiment protocols matter.** We find that 71% of reviewed field demonstrations used experiment protocols that may lead to unreliable savings estimates — for instance, benchmarking against simulations rather than measured baselines, or controlling only a portion of the building. These choices can systematically overestimate reported benefits.

- **Reliable savings estimates.** Among the 29% of tests we view as most trustworthy (measurement-based benchmarks, whole-building or properly accounted control, adequate test durations), the duration-weighted average utility bill savings are **16% for residential** and **13% for commercial** buildings.

- **Costs are rarely reported.** Only 13 of the 104 papers reported any information on deployment, operation, or maintenance costs — a critical gap for building the economic case for advanced HVAC control.

- **Recommendations for future work.** Based on gaps identified in the literature and the authors' collective experience conducting 21 field studies, we outline directions for future field research, including: improving experiment protocols, characterizing and reducing deployment costs, expanding hardware scope to include other distributed energy resources, and pursuing emerging objectives such as peak shaving and grid services.

---

## Repository Contents

This repository provides open-access data to support transparency and reproducibility.

| File | Description |
|------|-------------|
| `Field-Demonstration-Raw-Data-v1.xlsx` | Raw data extracted from all 104 reviewed papers, including study characteristics, experiment scopes, locations, HVAC systems, test durations, objectives, and reported outcomes |
| `Field-Demonstration-Checklist-v1.xlsx` | A checklist of recommended experiment protocols to guide future field demonstrations of MPC and RL for HVAC |

---

## Citation

> Khabbazi, A.J., Pergantis, E.N., Reyes Premer, L.D., Papageorgiou, P., Lee, A.H., Braun, J.E., Henze, G.P., & Kircher, K.J. (2025).
> **Lessons learned from field demonstrations of model predictive control and reinforcement learning for residential and commercial HVAC: A review.**
> *Applied Energy*, 399, 126459.
> https://doi.org/10.1016/j.apenergy.2025.126459

```bibtex
@article{khabbazi2025lessons,
  title   = {Lessons learned from field demonstrations of model predictive control
             and reinforcement learning for residential and commercial {HVAC}: {A} review},
  author  = {Khabbazi, Arash J. and Pergantis, Elias N. and {Reyes Premer}, Levi D.
             and Papageorgiou, Panagiotis and Lee, Alex H. and Braun, James E.
             and Henze, Gregor P. and Kircher, Kevin J.},
  journal = {Applied Energy},
  volume  = {399},
  pages   = {126459},
  year    = {2025},
  doi     = {10.1016/j.apenergy.2025.126459}
}
```

---

## Contact

For questions about the paper or data, please reach out to the corresponding author:

**Arash J. Khabbazi** — School of Mechanical Engineering, Purdue University
[arashjkh@purdue.edu](mailto:arashjkh@purdue.edu)
