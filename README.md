# Analysis of functional redundancy and divergence of seed-homologous microRNAs using a bioinformatical approach

This repository contains the code and data associated with the Master's thesis of Moris Ahmetašević, titled:

**"Analysis of functional redundancy and divergence of seed-homologous microRNAs using a bioinformatical approach"**  
Medical University of Innsbruck, Institute of Physiology (2025)

The project focuses on evaluating the functional overlap and complementary effects of miRNAs that share seed sequences, particularly in terms of pathway targeting and biological relevance. Predicted miRNA–mRNA interactions were analyzed using pathway enrichment and functional similarity approaches.

---

## Repository Structure

- **`data` branch**  
  Contains all input and output files used across the analysis.  
  Instructions for downloading these files are provided in [`instructions`]([https://github.com/kummer-lab/seed-mirna-functional-analysis/blob/data/Instructions]).

- **`notebooks` branch**  
  Contains the complete analysis pipeline, implemented in:
  - Python Jupyter Notebooks (`.ipynb`)
  - R Markdown files (`.Rmd`)

  Each notebook begins with a note linking it to the **Methods chapter section** of the thesis that it implements. These scripts cover preprocessing, prediction analysis and comparison to experimentally validated data, pathway enrichment, clustering of functional annotation terms, cluster similarity computation and subsequent cluster overlap analyses.
  For more information, read the corresponding Methods chapter of the thesis. 

---

## How to Reproduce the Study

1. Clone the repository
2. Check out the `data` branch and run the `download_data.sh` script to download all required files
3. Switch to the `notebooks` branch to follow the analysis pipeline
4. All required Python and R packages are listed in the respective notebooks

---

## Author

**Moris Ahmetašević**  
Medical University of Innsbruck  
Institute of Physiology  
2025
