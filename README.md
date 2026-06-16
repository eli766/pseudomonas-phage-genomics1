# pseudomonas-phage-genomics1
Comparative genomic analysis of P. aeruginosa phages from African isolates
# Comparative Genomic Analysis of Pseudomonas aeruginosa Phages from African Isolates

## Project Overview

This repository contains all code, notebooks, and documentation for a 
comparative genomic study of bacteriophages (phages) that infect 
*Pseudomonas aeruginosa* — a multidrug-resistant (MDR) pathogen of 
major clinical concern in East Africa and globally.

The study focuses on phage isolates from African sources and uses 
in silico (computational) approaches to characterize genomic diversity, 
annotate tail-associated proteins, and predict host range.

## Research Question

What are the genomic and proteomic features of *P. aeruginosa*-infecting 
bacteriophages isolated in Africa, and how do tail fibre and tail spike 
protein diversity predict host range breadth among clinically relevant 
MDR strains?

## Objectives

1. Compile and curate a high-quality dataset of *P. aeruginosa* phage 
   genomes from African isolates
2. Perform genome annotation, taxonomic classification, and comparative 
   genomic analysis
3. Characterize tail fibre and tail spike proteins using structural 
   modelling approaches
4. Predict phage host range based on genomic and protein features

## Hypotheses

- **H1:** African *P. aeruginosa* phages show significant genomic 
  diversity compared to globally deposited phages
- **H2:** Tail fibre and tail spike proteins are the most variable 
  genomic regions and correlate with host range differences
- **H3:** A subset of African phage isolates will show broad host range 
  activity against MDR *P. aeruginosa* strains

## Repository Structure
pseudomonas-phage-genomics/

├── data/

│   ├── raw/          # Original downloaded sequences (read-only)

│   └── processed/    # Filtered and formatted sequences

├── scripts/          # Python and Bash analysis scripts

├── notebooks/        # Google Colab Jupyter notebooks

├── results/          # Analysis outputs

├── figures/          # All visualizations

├── tables/           # Summary tables and metadata

├── manuscripts/      # Paper drafts

└── README.md
## Tools and Software

| Tool | Purpose | Reference |
|------|---------|-----------|
| Pharokka | Phage genome annotation | Bouras et al., 2023 |
| Roary | Pan-genome analysis | Page et al., 2015 |
| Mauve | Whole-genome alignment | Darling et al., 2004 |
| AlphaFold | Protein structure prediction | Jumper et al., 2021 |
| RaFAH | Host range prediction | Coutinho et al., 2021 |

## Data Availability

Phage genome sequences are retrieved from:
- NCBI GenBank (https://www.ncbi.nlm.nih.gov/genbank/)
- IMG/VR v4 (https://img.jgi.doe.gov/vr/)
- Virus-Host DB (https://www.genome.jp/virushostdb/)

## Author

ELKANA MUDI   
ellycanamoody@gmail.com  
[Date started: June 2026]

## License

MIT License — see LICENSE file for details.
