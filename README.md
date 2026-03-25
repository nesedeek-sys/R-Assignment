Nesreen's R Assignment

This repository contains my submission for the R assignment. It is mainly about data inspection, processing, and visualization of SNP data from maize and teosinte.

Repository organization

README.md
Provides and overview of the contents of this repository.

Documentation.Rmd
An R Markdown file containing the code and explanation of the analysis workflow.

R_Assignment.html
The rendered output of the R Markdown document.

data/
Contains the maize and snp data:
fang_et_al_genotypes.txt
snp_position.txt

Output/
Contains the maize and teosine data, each one has two files that contains decreasing and increasing chromosomes:

10 files for increasing maize
10 files for decreasing maize
10 files for increasing teosinte
10 files for decreasing teosinte

visuals/
Contains plots generated in Part II. (Data Visualization).

Reproducibility

This analysis can be reproduced by opening R_Assignment_Tuqa.Rmd in RStudio and running all code chunks in order, or knitting the file to HTML. Running the analysis code will regenerate the files in output/processed_files/ and output/plots/. These regenerated files can be compared with the versions already included in the repository after downloading or cloning it from GitHub.
