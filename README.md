# Molecular-Dynamics-Simulation-of-Galangin-Bound-to-HTLV-1-Protease

This repository documents a molecular docking and molecular dynamics (MD)
simulation study investigating the interaction between **galangin** and
**human T-cell leukemia virus type 1 (HTLV-1) protease**.

The crystal structure of HTLV-1 protease complexed with the inhibitor
KNI-10562 (PDB ID: 3LIN) was used as the structural template. Galangin, a
naturally occurring flavonol, was evaluated for its binding stability and
dynamic behavior within the protease active site.

# System Preparation
The HTLV-1 protease structure was obtained from the Protein Data Bank.
The co-crystallized inhibitor was removed prior to docking, and galangin
was introduced into the binding site. The resulting protein–ligand complex
was prepared for MD simulation following standard preprocessing protocols.

# Molecular Dynamics Simulation
All molecular dynamics simulations were performed using **GROMACS** on a
Linux environment. The system was solvated, energy-minimized, equilibrated,
and subjected to a production MD run under periodic boundary conditions.

Simulation parameters were defined using standard GROMACS input files
(.mdp), and trajectories were generated for subsequent analysis.

# Trajectory Analysis
Post-simulation analyses were conducted to evaluate the structural stability
and dynamic properties of the galangin–HTLV-1 protease complex, including:

- **Root Mean Square Deviation (RMSD):** to assess overall conformational
  stability of the protein–ligand complex over time.
- **Root Mean Square Fluctuation (RMSF):** to examine residue-level flexibility
  and identify dynamic regions of the protease.
- **Solvent Accessible Surface Area (SASA):** to evaluate changes in surface
  exposure and protein compactness upon ligand binding.

# Results Overview
The computed RMSD, RMSF, and SASA profiles provide insight into the dynamic
stability of galangin within the HTLV-1 protease binding site and the
structural behavior of the protease during the simulation timeframe.

---

## Notes
This repository focuses on the simulation setup and trajectory-based analyses.
Raw trajectory files were excluded due to file size constraints; selected
analysis outputs and figures are provided.

