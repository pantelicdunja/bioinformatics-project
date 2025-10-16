# Bioinformatics Project — Genetic Data Analysis and Disease Association

This project implements a complete bioinformatics pipeline for analyzing genetic and phenotypic data.  
It includes data loading, Genome-Wide Association Study (GWAS), mutation grouping, gene mapping, biological process analysis, and Bayesian disease prediction modeling.  
The project was developed in Python using real genomic data from the 1000 Genomes Project.

## Features
- Load and convert VCF/BCF files into a structured pandas DataFrame  
- Perform GWAS analysis using chi-square test with Laplace correction and Bonferroni adjustment  
- Group statistically significant mutations based on correlation and genomic distance  
- Identify genes and biological processes associated with disease status  
- Build and evaluate Bayesian networks for disease prediction  
- Automated pipeline that connects all stages, from raw data to biological insights  

## Tools and Libraries
- Languages: Python  
- Libraries: pandas, numpy, scipy, pysam, tqdm, intervaltree, scikit-learn  
- Environment: Google Colab  
- Version Control: GitHub Classroom  

## Example Workflow
1. Load genotype and phenotype data  
2. Execute GWAS analysis to identify significant variants  
3. Group correlated mutations within genomic regions  
4. Map lead mutations to genes using interval trees  
5. Detect relevant biological pathways (KEGG analysis)  
6. Evaluate predictive accuracy with Bayesian models  

## Example Output
The pipeline produces:
- A ranked table of significant genetic variants (by p-value)  
- Grouped mutation clusters with genomic coordinates  
- Identified genes containing lead mutations  
- Biological processes with high overlap scores  
- Bayesian model accuracy, precision, and recall metrics  




