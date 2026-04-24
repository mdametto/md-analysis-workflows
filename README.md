# MD Analysis Workflows

This repository contains AMBER-based workflows for molecular dynamics (MD) trajectory analysis and binding free energy calculations (MM/PBSA).

## Overview

The goal of this repository is to organize reproducible workflows commonly used in biomolecular simulation studies, including protein–ligand, protein–peptide, and protein–protein systems.

## General workflow

This represents a typical pipeline in molecular dynamics studies, where the present repository focuses on the analysis stages.

1. System preparation  
2. Molecular dynamics simulation  
3. Trajectory post-processing  
4. Structural and dynamical analysis (focus of this repository)  
5. Energetic analysis (MM/PBSA)

## Main analyses

- RMSD  
- RMSF  
- Radius of gyration  
- Hydrogen bonds  
- Intermolecular contacts  
- Principal component analysis (PCA)  
- MM/PBSA binding free energy calculations  
- Per-residue energy decomposition  

## Main tools

- AMBER / cpptraj  
- MMPBSA.py / MMPBSA.py.MPI  
- Bash  
- Python (optional, for post-processing and plotting)

## Repository structure

- `cpptraj/` → trajectory analysis input files (to be added)  
- `mmpbsa/` → MM/PBSA input templates (to be added)  
- `bash/` → execution scripts (to be added)  
- `examples/` → workflow descriptions and usage  
- `plots/` → optional plotting scripts or outputs  

## Current status

Initial version under development. Workflows and templates will be added progressively.

## Author

Mariangela Dametto  
Computational Structural Biochemist
