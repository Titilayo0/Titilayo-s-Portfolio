# Titilayo-s-Portfolio

# [Project 1: To identify differentially expressed genes in microarray from GEO42568](.github/workflows/static.yml)

This is a project I completed for my masters program where I identified differentially expressed genes in breast cancer cells.

*Downloaded and untarred the supplementary files for GSE42568

*List and gunzip all .CEL files in the GSE42568 directory.

*Background Correction:Use the justRMA() function for background correction.

*Data Normalization: Extract phenotypic data from the obtained set and normalized column names in the expression data.

*Save the normalized expression data to a file named "visual_exp_data.txt."

*Convert Matrix to DataFrame

*Install Bioconductor Packages and create Design Matrix

*Obtain significant genes using topTable and extract DEGs

*Plot a volcano plot using ggplot2 to visualize DEGs.
