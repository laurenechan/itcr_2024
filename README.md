# README

Here's a draft README for the Acute Myeloid Leukemia Heatmap project:

# Acute Myeloid Leukemia Heatmap Analysis

This project analyzes RNA-seq data from acute myeloid leukemia (AML) model mice to identify patterns in gene expression across different AML subtypes and treatments.

## Software Requirements

To run this project, you'll need:

- R statistical computing environment
- R packages: pheatmap, magrittr, readr, dplyr, tibble, sessioninfo

## Last Updated

This project was last updated in October 2021.

## Goals

The primary goals of this project are to:

1. Load and preprocess RNA-seq data from AML model mice
2. Perform clustering and dimensionality reduction on the gene expression data  
3. Generate heatmaps to visualize sample and gene relationships
4. Identify genes with high variability across samples
5. Annotate the heatmap with sample metadata

## File Structure

The project files are organized as follows:

- Main R script: AcuteMyeloidLeukemiaHeatmap.R
- Data files:
  - Sample data: data/SRP070849.tsv
  - Metadata: data/metadata_SRP070849.tsv
- Plots: plots/
- Results: results/

## Installation

To install and run the project:

1. Clone the repository
2. Ensure you have R installed
3. Install required R packages:
   ```
   install.packages(c("pheatmap", "magrittr", "readr", "dplyr", "tibble", "sessioninfo"))
   ```
4. Run the main R script:
   ```
   Rscript -e "source('AcuteMyeloidLeukemiaHeatmap.R')"
   ```

## Usage

The project generates several outputs:

- Top 90 variable genes: results/top_90_var_genes.tsv
- Annotated heatmap: plots/aml_heatmap.png

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

This analysis was adapted from the refine.bio examples and uses data from Shih et al., 2017.

Citations:
[1] https://github.com/andreasbm/readme
[2] https://dev.to/yuridevat/how-to-create-a-good-readmemd-file-4pa2
[3] https://abhiappmobiledeveloper.medium.com/guide-to-writing-on-readme-md-markdown-file-for-github-project-8aad4e4e2a15
[4] https://everhour.com/blog/github-readme-template/
[5] https://github.com/social-science-data-editors/template_README/blob/master/template-README.md
[6] https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project
[7] https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
[8] https://dev.to/scottydocs/how-to-write-a-kickass-readme-5af9
[9] https://www.hatica.io/blog/best-practices-for-github-readme/
[10] https://stackoverflow.com/questions/9331281/how-can-i-test-what-my-readme-md-file-will-look-like-before-committing-to-github
