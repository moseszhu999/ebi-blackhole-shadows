# EBI Black Hole Shadows: Ray Tracing & Polarimetry

This repository contains the numerical implementation of the General Relativistic Ray Tracing (GRRT) code used in the paper:

**"Observable Signatures of Einstein-Born-Infeld Black Holes: Shadows and Polarimetric Features"**

**Authors:** Dapeng (Moses) Zhu, Emmanouil Markoulakis

## Overview

We investigate the strong-field regime of Einstein-Born-Infeld (EBI) theory in the context of rotating charged black holes. This codebase calculates:
1.  **Null Geodesics:** Photon trajectories in the effective optical metric of the KNBI spacetime.
2.  **Shadow Imaging:** The shape and size of the black hole shadow.
3.  **Polarimetry:** Vacuum birefringence effects and polarization transport vectors.

## Key Features

*   **Metric:** Kerr-Newman-Born-Infeld (KNBI) solution.
*   **Integrator:** 4th-order Runge-Kutta (RK4) with adaptive step size.
*   **Polarization:** Transport of the Walker-Penrose constant in the non-linear regime.

## Status

*   [x] Metric derivation and implementation
*   [x] Geodesic integrator
*   [x] Shadow boundary determination
*   [ ] Code cleanup and documentation for public release

## Data Availability

The full source code and datasets generating the figures in the manuscript will be made publicly available here upon acceptance of the paper.

For immediate inquiries or collaboration requests regarding the code, please contact the corresponding author: `moseszhu999@gmail.com`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
