# Module 5.4: R Exercise – Phylograms of the IGF1 gene in vertebrates

## Overview
In this exercise we will use the package "phangorn" which includes different methods to perform phylogenetic analysis in R. We'll build phylogenetic trees based on amino acid sequence alignments and evaluate them in an evolutionary context. This allows us to investigate evolutionary relationships among species and explore patterns of molecular conservation and divergence. In this exercise, you'll explore three methods for building phylogenetic trees from amino acid sequence alignments:
 - *UPGMA* (a distance-based clustering method that assumes a molecular clock),
 - *Neighbor-joining* (a distance-based method that does not assume a molecular clock), and
 - *Maximum likelihood* (a model-based method for identifying the best tree given the data).

## Files Included

- `module_5-4_phylograms.Rmd` – R Markdown file for the exercise (submit knitted PDF)
- `module_5-4.data.zip` contains input data file for the exercise:
  -  `igf1.fasta`

## Instructions

1. **Open** the `module_5-4_phylograms.Rmd` file in RStudio.

2. **Unzip** `module_5-4.data.zip` and make sure `igf1.fasta` and `module_5-4_phylograms.Rmd` are in the same directory.

3. Run each code chunk in order. Read the instructions and answer questions as you go.

4. If this is your first time, **install the required packages** by uncommenting and running the `install.packages()` lines at the top of the file.

5. Knit the file to PDF when finished and upload it to **Gradescope**.

## 📚 Useful Resources
 - phangorn vignette
   - [Estimating phylogenetic trees with phangorn](https://cran.r-project.org/web/packages/phangorn/vignettes/Trees.html)
 - phangorn paper
   - [phangorn: phylogenetic analysis in R](https://academic.oup.com/bioinformatics/article/27/4/592/198887)
 - Substitution models in phylogenetics
   - [Trends in substitution models of molecular evolution](https://pmc.ncbi.nlm.nih.gov/articles/PMC4620419/)
   - See "Introduction" and "Trends in DNA substitution models"
 - Unweighted Pair-Cluster Method using Arithmetic Averages (UPGMA) method
   - [UPGMA](https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/upgma)
 - Neighbor-joining method
   - [Original paper](https://academic.oup.com/mbe/article/4/4/406/1029664)
   - More about the method (with pictures!): [Bioinformatics by hand: Neighbor-joining trees](https://www.tenderisthebyte.com/blog/2022/08/31/neighbor-joining-trees/)
 - Maximum Likelihood method
   - [Maximum Likelihood Phylogenetic Inference](https://www.sciencedirect.com/science/article/pii/B9780128000496002079)