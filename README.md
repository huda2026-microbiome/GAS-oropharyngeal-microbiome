# GAS-oropharyngeal-microbiome

Code and processed data supporting the analysis of the oropharyngeal microbiome in remote-living Australian children with and without Group A Streptococcal infection.

This repository contains the downstream R analysis used to reproduce the microbiome analyses and figures reported in the manuscript.

## Data

`physeq_clean_github.rds` contains the decontam-filtered phyloseq object used for downstream analyses.
Raw sequencing data are deposited separately in a public sequence repository.

## Analysis

The R Markdown analysis file will contain the code used for:

- alpha diversity
- Bray-Curtis dissimilarity
- PCoA
- PERMANOVA
- longitudinal GAS acquisition and loss analyses
- symptom development analyses
- taxonomic visualisations
- supplementary analyses

## Reproducibility

Package versions and session information are provided at the end of the R Markdown analysis.
