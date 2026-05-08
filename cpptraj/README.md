# cpptraj Input Files

This directory contains cpptraj input templates for molecular dynamics trajectory analysis.

## Available templates

- `rmsd_equilibration_check.in` → RMSD calculation to evaluate trajectory stability and define equilibrated regions.

## Notes

Residue masks, trajectory names, and output filenames should be adapted according to each molecular system.

## How to run

```bash
cpptraj -p system.prmtop < cpptraj/rmsd_equilibration_check.in > rmsd.out
```
