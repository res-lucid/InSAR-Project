# InSAR Project - 2026 Honours Research Project

## Project Overview

A study investigating unsupervised clustering techniques for interpreting InSAR displacement time-series data of tailings storage facility (TSF) failures.

## Repository Structure

- `data/` - InSAR time-series datasets as CSV files (already processed).
- `notebooks/` - R Markdown notebooks containing analyses: Split into 3 stages and also includes early experimenting notebooks.
- `outputs/` - Generated results: CSV files and plots.

## R Setup

All analyses were conducted in R/RStudio (Version: 2026.08.0+187).

Required packages for running the notebooks:

```r
install.packages(c(
	"readxl",
	"ggplot2",
	"factoextra",
	"gridExtra",
	"cluster",
	"clusterSim",
	"dbscan",
	"dtwclust",
	"patchwork",
	"ggplotify",
	"zoo",
    "tidyr",
    "dplyr"
))
