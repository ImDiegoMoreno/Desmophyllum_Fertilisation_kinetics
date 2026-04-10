# Desmophyllum_Fertilisation_kinetics

Bayesian modelling framework for analysing fertilisation kinetics, sperm motility, and gamete interaction processes in *Desmophyllum* corals.

## Repository structure

This repository is organised by **analysis module**, corresponding to the main sections of the manuscript:

- **Motility/**
- **Fertilisation/**
- **Contact_time/**

Each module contains a consistent internal structure:
folder_name:
- R/         # R Markdown scripts (analysis workflows)
- data/      # Input and processed datasets
- figures/   # Generated figures
- tables/    # Output tables (main text and supplementary)

## Notes

- File paths are written relative to each module folder to ensure portability  
- Supplementary outputs (tables and figures) are generated within the same workflow as main results  
- Some scripts include additional diagnostic or exploratory steps that are not part of the final manuscript outputs but are retained for transparency  

## Author

Diego Moreno Morán
