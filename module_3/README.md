# Module 3.8: R Exercise – RNA-seq Differential Expression in Fruit Fly Development

This folder contains the R exercise for Module 3.8 in BIO 543 (Summer 2025):  
**"R exercise: RNASeq – Differential Expression in *Drosophila melanogaster***"

## 🧪 Overview

In this exercise, you’ll analyze RNA-seq count data from fruit fly (*Drosophila*) larvae at different developmental stages (L1 vs L2) using the DESeq2 package in R. You will:
- Load and inspect count and phenotype data
- Run a differential expression analysis
- Visualize results (MA plot, volcano plot, heatmap)
- Identify top genes and explore their expression
- Interpret biological meaning in the context of gene regulation

## 📂 Files Included

- `module3_exercise.Rmd` – R Markdown file for the exercise
- `Module_3-8_data.zip` – zipped archive containing the following files:
  - `modencodefly_count_table.txt` – RNA-seq count data
  - `modencodefly_phenodata.txt` – sample metadata

## 📥 Instructions

1. **Download and unzip** the file `Module_3-8_data.zip`.

2. Place the two unzipped files in the **same folder** as the R Markdown file:

3. Open the `.Rmd` file in RStudio.

4. Make sure your working directory is set to the folder containing all three files. You can check this in R with:
```r
getwd()
```

5. Knit the document or run the code chunks interactively.

The .Rmd script includes a check that will stop with an error message if the required data files aren’t found in the same folder.

## 📚 Useful Resources
 - DESeq2 Bioconductor vignette:
https://bioconductor.org/packages/devel/bioc/vignettes/DESeq2/inst/doc/DESeq2.html

 - FlyBase gene lookup:
https://flybase.org/

For questions or help, post in the Yellowdig discussion board, attend TA office hours, or reach out to the TA and/or instructor directly.
