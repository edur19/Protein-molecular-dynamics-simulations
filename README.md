# GROMACS Protein molecular dynamics simulations under different conditions
The pdf is the exam realized using gromacs to analyzed the molecular dynamics simulations of a protein under solvated and vacuum conditions. It was analyzed the RMSD, RMSF, radius of gyration and energy profiles, demonstrating the critical role of solvent in maintaning structural stability and realistic behavior.
The class was given by the max planc institute for polymer research at the Heidelberg University: https://www.mpip-mainz.mpg.de/ws-2025-26-lectures-and-hands-on-sessions-in-computational-molecular-biophysics

## Folder Description
md_vacuum/

Contains molecular dynamics simulations performed under vacuum conditions without explicit solvent molecules.

This setup was used to evaluate structural instability and artificial conformational changes caused by the absence of solvent interactions.

Main files include:

trajectory files (.trr, .xtc)
topology and parameter files (.tpr, .mdp)
energy analysis (energy.xvg)
RMSD and gyration analyses (rmsd.xvg, gyrate.xvg)
protein structure snapshots (.pdb, .gro)

md_solvated/

Contains molecular dynamics simulations performed in an explicit water-solvated environment.

This simulation reproduces more realistic biological conditions and was used to analyze protein stability, flexibility, and energetic behavior in solution.

Analyses include the same as before.

The solvated system demonstrated improved structural stability compared with vacuum simulations.

## Key Findings
The vacuum simulation showed larger structural deviations and instability, while the solvated system maintained more realistic conformational behavior, highlighting the critical role of solvent interactions in protein stability.
