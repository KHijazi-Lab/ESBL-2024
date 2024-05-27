# Isolate Clustering and Temporal Analysis README

This repository contains R scripts for conducting isolate clustering based on SNP distances and temporal analysis of genetic data. The scripts are designed to explore genetic relationships between isolates, visualize temporal trends, and provide insights into the dynamics of genetic variation over time.

## Files

1. `isolate_clustering.R`: This script performs hierarchical clustering on SNP distances between isolates and visualizes the results using dendrograms. It also calculates and plots the average SNP distance over time.

2. `temporal_analysis.R`: This script focuses on temporal analysis of SNP data, including data preprocessing, time-series creation, imputation of missing values, fitting of GAM models, and visualization of temporal trends.

## Usage

1. **Installation:** Ensure you have R installed on your system.
2. **Cloning:** Clone or download this repository to your local machine.
3. **Execution:** Open the desired R script in RStudio or any text editor that supports R scripts.
4. **Modification:** Modify the file paths or parameters as needed to suit your data and analysis requirements.
5. **Execution:** Run the script in its entirety or execute specific sections sequentially.

## Dependencies

The scripts utilize the following R packages:
- `tidyverse`: For data manipulation and visualization.
- `ggplot2`: For advanced plotting capabilities.
- `dendextend`: For manipulation and visualization of dendrograms.
- Additional packages as mentioned in the individual scripts.

Ensure these packages are installed before running the scripts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
