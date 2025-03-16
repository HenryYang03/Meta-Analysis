# Meta-Analysis
This repository contains the code files for the paper: Evaluating the potential of acupuncture for Alzheimer’s disease treatment: A meta-analysis and systematic review of mouse model studies

---

## Requirements

### Software
- [R](https://www.r-project.org/) (version ≥ 4.0.0)
- [RStudio](https://posit.co/download/rstudio/)

### R Libraries
Before running the `.Rmd` file, ensure you have the following libraries installed:
```r
install.packages(c("meta", "metafor", "metasens", "dplyr", "readxl", "ggplot2", "netmeta", "igraph", "dmetar", "Cairo"))
```

---

## How to Use

### Set Up the Data Directory
The RMarkdown files for each outcome variable relies on `data_dir` variable. Set the data_dir path to be:
```
Notes and data for listed articles
```
which is provided in the repo.

---

## Outputs

### Meta-Analysis Outputs
- **Forest Plot**: Visualizes meta-analysis results.
- **Funnel Plot**: Identifies potential publication bias.
- **Bias Assessment**: Performed using the `metabias` and `trimfill` functions.

### Network Meta-Analysis Outputs
- **Network Graph**: Visualizes the relationships between treatment and control groups.
- **Network Forest Plot**: Summarizes the results of the network meta-analysis.

---
