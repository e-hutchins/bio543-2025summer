
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

- `VcfR`: a package to manipulate and visualize VCF data in R
    - [Installation Instructions, Vignettes](https://github.com/knausb/vcfR?tab=readme-ov-file#download)
    - [Reference Manual](https://cran.r-project.org/web/packages/vcfR/vcfR.pdf)
    - [Documentation](https://github.com/knausb/vcfR_documentation)
    - [GitHub repo](https://github.com/knausb/vcfR)
- `ape`: Analysis of Phylogenetics and Evolution
    - [Homepage](https://emmanuelparadis.github.io/)
    - [Reference manual](https://cran.r-project.org/web/packages/ape/ape.pdf)
    - [dev GitHub repo](https://github.com/emmanuelparadis/ape)
- Reference Dataset: [Haas et al., Nature, 2009](https://www.nature.com/articles/nature08358) – *Genome sequence and analysis of the Irish potato famine pathogen*

## Further Exploration of Variants with Bioconductor
 - [Variant Annotation package](https://bioconductor.org/packages/release/bioc/html/VariantAnnotation.html)
    - [VariantAnnotation Introduction](https://www.bioconductor.org/packages/devel/bioc/vignettes/VariantAnnotation/inst/doc/VariantAnnotation.html)
    - [Using filterVcf() to Select Variants from VCF Files](https://bioconductor.org/packages/release/bioc/vignettes/VariantAnnotation/inst/doc/filterVcf.html)
    - [ensemblVEP: using the REST API with Bioconductor](https://bioconductor.org/packages/release/bioc/vignettes/VariantAnnotation/inst/doc/ensemblVEP.html)

For questions or help, post on Yellowdig, attend TA office hours, or contact your instructor.
