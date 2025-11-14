# Atomistic-Modeling-of-Argon-MS-MD-
Implementing molecular statics (MS) and molecular dynamics (MD) simulations of Lennard-Jones Argon clusters to study structural relaxation, energy evolution, and temperature-dependent phase behavior. All simulations were performed on free-surface FCC clusters using a spline-smoothed LJ potential and integrated with the Velocity Verlet algorithm.
Project Overview
1. Molecular Statics (MS) Relaxation

Constructed simple-cubic and FCC Argon clusters (500+ atoms) and relaxed them using steepest-descent optimization.

Evaluated energy convergence, maximum force decay, stress tensor evolution, hydrostatic pressure, and RDFs to confirm equilibrium structures.

2. Molecular Dynamics (MD) Simulations

Implemented Velocity Verlet integration to simulate equilibrium MD of Lennard-Jones Argon from 0 to 100 K.

Computed and visualized:

Potential, kinetic, and total energy evolution

Temperature fluctuations

Hydrostatic pressure

Radial Distribution Function (RDF)

Velocity Autocorrelation Function (VACF)

3D atomic configurations

**Key Findings**
Crystalline stability up to ~50 K indicated by sharp RDF peaks and oscillatory VACF.

Near 100 K, RDF peak broadening and VACF decay show loss of long-range order → onset of liquid-like behavior.

Energy and pressure trends agree with expected Lennard-Jones solid–liquid transition behavior.
