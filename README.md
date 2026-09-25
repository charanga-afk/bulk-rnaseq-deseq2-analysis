# Bulk RNA-seq Differential Expression Analysis

## Overview

This project presents a reproducible bulk RNA-seq differential expression
analysis workflow using public transcriptomic data.

##The analysis includes:

- Quality control
- Data preprocessing
- Count matrix exploration
- Normalization
- Principal Component Analysis (PCA)
- Differential expression analysis using DESeq2
- MA plot
- Volcano plot
- Heatmap
- Pathway enrichment analysis

## Biological Question

Which genes are differentially expressed between normal and tumor samples?

## Tools

- R
- RStudio
- DESeq2
- ggplot2
- pheatmap
- clusterProfiler

## Reproducibility
All analyses are implemented using R scripts so that the workflow can
be reproduced from the input data.

## Project Structure

```text
data/       Input datasets
scripts/    R analysis scripts
results/    Tables and figures
docs/       Interpretation and documentation
