
# Module 4.6: R Exercise – Genetic Variation in *Phytophthora infestans*

## Overview

In this exercise, you’ll explore genetic variants across multiple isolates of the fungus *Phytophthora infestans* using the `vcfR` package in R. You will:

- Load variant (VCF), genome sequence (FASTA), and annotation (GFF) data
- Create and visualize a `chromR` object
- Apply filters to mask low-quality variants
- Zoom into specific regions of the genome
- Identify genes that overlap regions of interest
- Connect genetic variant patterns to biological function

## Files Included

- `module_4-6_variants.Rmd` – R Markdown file for the exercise (submit knitted PDF)
- Built-in `pinfsc50` package dataset (no separate download required)

## Instructions

1. **Open** the `module_4-6_variants.Rmd` file in RStudio.

2. Run each code chunk in order. Read the instructions and answer questions as you go.

3. If this is your first time, **install the required packages** by uncommenting and running the `install.packages()` lines at the top of the file.

4. Knit the file to PDF when finished and upload it to **Gradescope**.

The data used in this module comes with the `vcfR` package - no external files are required.

## Common Issues

- If you see an error like `package not found`, uncomment the install line and run it.
- If a plot doesn’t render, make sure the correct object exists and the filtering step ran successfully.
- If knitting fails, try running all chunks manually first.

## 📚 Useful Resources

- `vcfR` documentation: https://cran.r-project.org/web/packages/vcfR/vcfR.pdf
- Bioconductor Variant Annotation Workflow: https://bioconductor.org/help/workflows/variantAnnotation/
- Reference: Haas et al., Nature, 2009 – *Genome sequence and analysis of the Irish potato famine pathogen*

For questions or help, post on Yellowdig, attend TA office hours, or contact your instructor.
