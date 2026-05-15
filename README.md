# GROMACS Protein molecular dynamics simulations under different conditions
The PDF contains the final project developed using GROMACS to analyze molecular dynamics simulations of a protein under solvated and vacuum conditions.

The study included the analysis of RMSD, RMSF, radius of gyration, and energy profiles, demonstrating the critical role of solvent interactions in maintaining structural stability and realistic protein behavior.

This course was taken during my Master's exchange in Heidelberg, offered by the Max Planck Institute for Polymer Research in collaboration with Heidelberg University.
https://www.mpip-mainz.mpg.de/ws-2025-26-lectures-and-hands-on-sessions-in-computational-molecular-biophysics


## Folder Description
md_vacuum/
<img width="2534" height="1586" alt="image" src="https://github.com/user-attachments/assets/e2b408a5-2184-4d8c-8949-1c4077c075cf" />

Contains molecular dynamics simulations performed under vacuum conditions without explicit solvent molecules.

This setup was used to evaluate structural instability and artificial conformational changes caused by the absence of solvent interactions.

Main files include:

trajectory files (.trr, .xtc)
topology and parameter files (.tpr, .mdp)
energy analysis (energy.xvg)
RMSD and gyration analyses (rmsd.xvg, gyrate.xvg)
protein structure snapshots (.pdb, .gro)

md_solvated/
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/b20cae03-d36d-42b0-9fd0-83610ff232ca" />

Contains molecular dynamics simulations performed in an explicit water-solvated environment.

This simulation reproduces more realistic biological conditions and was used to analyze protein stability, flexibility, and energetic behavior in solution.

Analyses include the same as before.

The solvated system demonstrated improved structural stability compared with vacuum simulations.

## Key Findings
The vacuum simulation showed larger structural deviations and instability, while the solvated system maintained more realistic conformational behavior, highlighting the critical role of solvent interactions in protein stability.
