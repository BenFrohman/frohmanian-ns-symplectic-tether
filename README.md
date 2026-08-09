# Frohmanian Symplectic Tether

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

A geometric program for the **3D incompressible Navier–Stokes global-regularity problem**, centered on the
*Frohmanian Symplectic Tether* — a construction on coadjoint orbits that produces controllable negative
feedback at maxima of the vorticity, coupled to a tethered Lyapunov / enstrophy argument.

This repository is the landing page for the program. The **Lean 4 formalization**, blueprint, and manuscripts
live in the companion repository:

➡️ **[BenFrohman/NS_Millennium_Proof](https://github.com/BenFrohman/NS_Millennium_Proof)**

> ### Honest scope
> This is an active research program and a **priority-preserving** body of work. It contains novel geometric
> definitions and architecture, schematic proof skeletons, and remaining analytic work. **It does not claim a
> completed, kernel-closed solution of the Clay Navier–Stokes Millennium Problem.**

## Core ideas

- **Symplectic tether on coadjoint orbits** with three necessary conditions (C1)–(C3) and a degeneracy result
  with respect to the kinetic-energy Hamiltonian.
- **Two-layer, non-circular architecture**: a geometric layer followed by an analytic (tethered Lyapunov /
  enstrophy) layer.
- **Independent majorant** controlling the vorticity-stretching term via higher-order dissipation.

## Authorship and priority

Original author and originator: **Benjamin Stanley Frohman** (@Investor0x / Bit21), 2026. The named
constructions above are original to this work. See the companion repository's `AUTHORS.md`, `CITATION.cff`, and
history for attribution and provenance.

## License

[Apache License 2.0](LICENSE) © 2026 Benjamin Stanley Frohman.
