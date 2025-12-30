# DESeq2-PCA-RNAseq-Tutorial

# DESeq2 PCA Analysis for RNA-seq Data (airway dataset)

This repository provides a beginner-friendly introduction to **PCA (Principal Component Analysis)** applied to RNA-seq data using **DESeq2** in R.

The tutorial is designed for **undergraduate-level bioinformatics and biotechnology students**, focusing on *why* each step is performed rather than just *how* to run the code.


## Contents

- Conceptual explanation of PCA in RNA-seq analysis
- Data requirements and assumptions for PCA
- Introduction to DESeq2 and its role in RNA-seq workflows
- Variance Stabilizing Transformation (VST)
- PCA visualization and interpretation
- Practical example using the **airway** RNA-seq dataset


## Dataset

The analysis uses the **airway** dataset, a small and well-curated RNA-seq dataset commonly used for teaching purposes.

The dataset includes:
- Raw RNA-seq count matrix (genes × samples)
- Sample metadata (control vs treatment)
- Clear experimental design suitable for PCA visualization

## Workflow Overview
counts + metadata + design + DESeq2 + VST + PCA
This workflow represents the standard exploratory analysis pipeline for bulk RNA-seq data.

## Files

- `DESeq2_PCA_airway.Rmd`  
  R Markdown file containing explanations, code, and analysis.

- `DESeq2_PCA_airway.html`  
  Rendered HTML output of the analysis.

## Requirements

- R (≥ 4.2 recommended)
- R packages:
  - `DESeq2`
  - `airway`

Packages should be installed **before** running the analysis.

## Target Audience

- Undergraduate students in Biotechnology / Bioinformatics
- Researchers new to RNA-seq exploratory data analysis
- Anyone learning PCA interpretation in biological data

---

## License

This project is released under the **MIT License**.  
You are free to use, modify, and share the material with proper attribution.

---

## Author

**Oğuzhan Işılay**  
Undergraduate student in Biotechnology  
Interested in bioinformatics, RNA-seq analysis, and data visualization


## Notes

This repository is intended for educational purposes.  
For large-scale or clinical RNA-seq studies, additional quality control and statistical considerations are required.


