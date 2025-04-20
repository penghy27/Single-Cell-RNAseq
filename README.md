# README: 

This repository contains two analyses related to single-cell RNA sequencing (scRNA-seq):

1. **Zebrafish Embryo scRNA-seq Analysis**: An analysis of single-cell RNA sequencing data from zebrafish embryos under high-glucose condition.
2. **Signac_scATAC Analysis**: A workflow for analyzing single-cell ATAC-seq data using the Signac package, integrated with scRNA-seq for cell type annotation.

----------------------------------
## Zebrafish Embryo scRNA-seq Analysis

### Overview
This repository contains single-cell RNA sequencing (scRNA-seq) analysis of zebrafish embryos under control and high-glucose conditions. The primary goal is to investigate the transcriptomic effects of a high-glucose environment on embryonic development, leveraging data from the GEO dataset GSE276251. The analysis is performed using the Seurat v5 package in R, following a standard scRNA-seq workflow with modern enhancements like SCTransform for normalization and integration.

### Analysis Workflow
1. Data Loading and Preprocessing
2. Quality Control (QC)
3. Normalization and Integration
4. Dimensionality Reduction
5. Clustering
6. Differential Expression Analysis
7. Cell Type Annotation 
8. Pathway Enrichment Analysis

------------------------------------------
## Signac_scATAC Analysis
This document provides a step-by-step workflow for analyzing single-cell ATAC-seq (scATAC-seq) data using the **Signac** package in R. The analysis focuses on processing chromatin accessibility data from human PBMCs (Peripheral Blood Mononuclear Cells) and integrating it with scRNA-seq data for cell type annotation and differential accessibility analysis.

### Workflow
1. Data Preprocessing:
2. Quality Control (QC):
3. Normalization and Dimensionality Reduction:
4. Non-linear Dimensionality Reduction and Clustering:
5. Gene Activity Matrix:
6. Integration with scRNA-seq Data:
7. Differential Accessibility Analysis:
8. Visualization:
  - Plot genomic regions to visualize accessibility patterns near key marker genes.
  - Highlight differentially accessible peaks in the genomic context.

### Key Outputs
- Clustered UMAP plots showing cell type annotations.
- Differential accessibility peaks between cell types.
- GO enrichment analysis results for genes near differentially accessible peaks.
- Genomic region plots showing accessibility patterns near key marker genes.
