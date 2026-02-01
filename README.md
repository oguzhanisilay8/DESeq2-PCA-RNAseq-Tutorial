# DESeq2 PCA Analysis for RNA-seq Data (airway dataset)

This repository provides a beginner-friendly introduction to **Principal Component Analysis (PCA)** applied to RNA-seq data using the **DESeq2** package in R.

The tutorial is designed for undergraduate-level bioinformatics and biotechnology students, with a strong focus on understanding *why* each analytical step is performed rather than only *how* to execute the code.

---

## Contents

This tutorial covers the following topics:

- Conceptual explanation of PCA in RNA-seq analysis  
- Data requirements and assumptions for PCA  
- Introduction to DESeq2 and its role in RNA-seq workflows  
- Variance Stabilizing Transformation (VST)  
- PCA visualization and interpretation  
- Practical example using the **airway** RNA-seq dataset  

---

## Dataset

The analysis is based on the **airway** dataset, a well-curated RNA-seq dataset commonly used for teaching and demonstration purposes.

The dataset includes:

- Raw RNA-seq count matrix (genes × samples)  
- Sample metadata (control vs treatment groups)  
- A clear experimental design suitable for PCA visualization  

---

## Workflow Overview

The analysis follows a standard exploratory RNA-seq pipeline:
Counts + Metadata → DESeq2 → VST → PCA → Visualization
This workflow represents a typical quality control and exploratory analysis strategy for bulk RNA-seq data.

---
## Files

- `DESeq2_PCA_airway.Rmd`  
  R Markdown file containing explanations, code, and analysis.

- `DESeq2_PCA_airway.html`  
  Rendered HTML output of the complete workflow.

- `docs/index.html`  
  GitHub Pages output for the tutorial (same content as the HTML report), accessible at:
---

## Requirements

- R (version ≥ 4.2 recommended)  
- Required R packages:
  - `DESeq2`  
  - `airway`  

Packages should be installed before running the analysis.

---

## How to Run

1. Clone or download this repository.  
2. Open `DESeq2_PCA_airway.Rmd` in RStudio.  
3. Install required packages if needed.  
4. Render the file to HTML using:

```r
rmarkdown::render("DESeq2_PCA_airway.Rmd")
```
The rendered HTML file will contain the complete analysis and explanations.

## Target Audience

This repository is intended for:

Undergraduate students in Biotechnology and Bioinformatics

Researchers new to RNA-seq exploratory data analysis

Learners interested in PCA interpretation in biological data

## Educational Purpose

This material is designed for educational use and emphasizes:

Step-by-step explanation of analytical logic

Interpretation of PCA results in biological context

Understanding quality control in RNA-seq workflows

For large-scale or clinical RNA-seq studies, additional statistical modeling and quality control procedures are required.

## AI Assistance Disclosure

Artificial intelligence tools were partially used to improve documentation structure, clarity, and organization. All analytical workflows, interpretations, and final validations were performed by the author.

## Author

Oğuzhan Işılay
Undergraduate Student in Biotechnology and Bioinformatics
Mersin University, Türkiye

Interests: Bioinformatics, RNA-seq Analysis, Data Visualization

GitHub: https://github.com/oguzhanisilay8

## License

This project is released under the MIT License.

You are free to use, modify, and share the material with proper attribution.

