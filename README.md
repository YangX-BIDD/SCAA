# Single-Cell Analysis of Aortic Aneurysm (SCAA)

This project is focused on the single-cell analysis of aortic aneurysms, using state-of-the-art tools for data preprocessing, clustering, cell-type annotation, and pathway enrichment analysis.

## Features
- **Data Preprocessing**: Quality control, normalization, and filtering of single-cell RNA sequencing data.
- **Clustering and Annotation**: Leiden clustering and automatic cell-type annotation using pySCSA.
- **Pathway Analysis**: Enrichment analysis for key genes and pathways.
- **Visualization**: UMAP, heatmaps, pseudotime analysis, and gene expression plots.

## Data
Raw and processed data are stored in the `data/` directory. Make sure to place your raw data files in the `raw_data/` subdirectory.

## Installation
Install the required dependencies:
```bash
pip install -r requirements.txt
