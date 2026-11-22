[![DOI](https://zenodo.org/badge/1466929110.svg)](https://doi.org/10.5281/zenodo.24428110)
# Topological Emergence and Dimensional Projection of Time (v1.2.2)

**Author:** E. R. dos Santos  
**License:** GNU General Public License v3.0 (GPLv3)

## Overview
This repository contains the reference Python implementation and accompanying theoretical manuscript (`Topological_Emergence_v1.2.2.pdf`) for an exploratory effective field framework investigating the emergence of spatial metric scales, gauge couplings, gravitational rigidity, and Standard Model particle mass hierarchies from discrete topological defects in a primordial temporal substrate.

## Conceptual Architecture
1. **Pre-Geometric Substrate & Symmetry Breaking:** The Heisenberg quantum non-nullity bound ($\Delta E \cdot \Delta t \ge \hbar/2$) precludes a strictly static zero-action vacuum ($S = 0$), inducing a minimal primordial phase action $S_0 = 1/2$.
2. **KAM Stability & Lattice Crystallization:** Non-linear phase dynamics destabilize rational frequency modes, preserving the golden ratio $\phi = (1 + \sqrt{5})/2$ as the unique invariant torus (KAM theorem). Critical percolation crystallizes into 3D icosahedral/FCC ($z_{3d} = 12$) and 4D $D_4$ ($z_{4d} = 24$) packings with frustration density $\rho_v^* = (z_{3d} - \chi_0)^{-1} = 0.1$ ($\chi = 2.1$) and variational curvature defect $d^* = \frac{1}{2}\phi^{-1/3} \approx 0.425900$.
3. **Unified Physical Ontology:**
   - **Matter:** Topologically confined temporal folds (spin-1/2 double-cover defects across $2z_{4d} = 48$ states and Skyrme solitons).
   - **Gauge Forces:** Geometric phase connections across lattice coordination neighborhoods ($\sin^2\theta_W = 3/13$).
   - **Gravity:** Macroscopic elastic rigidity of the emergent mesh reacting to localized concentrations of confined energy.

## Usage
Requires Python 3.8+ (uses only the standard `math` library, zero external dependencies):

```bash
python topological_emergence.py
```

## Summary of NLO Benchmarks
| Observable | Model (NLO) | Reference (PDG / CODATA) | Tension / Deviation |
| :--- | :--- | :--- | :--- |
| $M_p$ (GeV) | $0.9416 \pm 0.0022$ | $0.9383$ | $1.5\sigma$ |
| $\alpha^{-1}(0)$ | $137.1050 \pm 0.2943$ | $137.0360$ | $0.2\sigma$ |
| $m_e$ (MeV) | $0.5136 \pm 0.0016$ | $0.5110$ | $1.6\sigma$ |
| $m_\mu$ (MeV) | $105.6326 \pm 0.2452$ | $105.6584$ | $0.1\sigma$ |
| $m_\tau$ (MeV) | $1777.3743 \pm 4.1399$ | $1776.8600$ | $0.1\sigma$ |
| $v_{\text{Higgs}}$ (GeV) | $245.1413 \pm 0.7752$ | $246.2197$ | $1.4\sigma$ |
| $m_t$ (GeV) | $172.8284 \pm 0.5465$ | $172.6900$ | $0.3\sigma$ |
| $M_W$ (GeV) | $80.6373 \pm 0.2286$ | $80.3770$ | $1.1\sigma$ |
| $M_Z$ (GeV) | $91.2256 \pm 0.2586$ | $91.1876$ | $0.1\sigma$ |
| $M_H$ (GeV) | $125.4379 \pm 0.3966$ | $125.2500$ | $0.5\sigma$ |
| $a_e$ | $0.0011585$ | $0.0011597$ | $0.3\sigma$ ($0.10\%$) |
| $a_0$ (\AA) | $0.5267$ | $0.5292$ | $1.0\sigma$ ($0.46\%$) |
| $R_\infty$ (eV) | $13.6621$ | $13.6057$ | $0.6\sigma$ ($0.41\%$) |

### Falsifiable BSM Candidates
- **Heavy Icosahedral Scalar ($M_{H_2}$):** $600.47 \pm 1.90\text{ GeV}$ (HL-LHC)
- **Topological QCD Axion ($m_a$):** $0.376\text{ meV}$ ($375.8\,\mu\text{eV}$, $\nu \approx 90.9\text{ GHz}$) at $f_a \approx 1.52 \times 10^{10}\text{ GeV}$ (MADMAX)

## Methodological Transparency Note
The conceptual formulation, theoretical axioms, and architecture of this model were idealized by **E. R. dos Santos**. The logical implementation in Python, mathematical structuring, and code refactoring were developed with the assistance of Artificial Intelligence.

This work does not aim, in any way or at any time, to exhaust the subject, supersede similar research, or provide definitive answers of any kind under any aspect. All numerical results, equations, and computational routines are available for reading, auditing, testing, and modification under the terms of the GNU GPLv3.
