# InSAR Project - 2026 Honours Research Project

## Project Overview

A study investigating data science techniques (particularly unsupervised clustering) for interpreting InSAR displacement time-series data of tailings storage facility (TSF) failures.

## Repository Structure

- `data/` - InSAR time-series datasets (already processed)
- `notebooks/` - R Markdown notebooks containing analyses
- `outputs/` - Generated results and plots

## R Setup

All analyses were conducted in R/RStudio (Version: 2026.08.0+187)

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
	"zoo"
))