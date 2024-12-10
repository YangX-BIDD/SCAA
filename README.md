**# Single-Cell Analysis of Aneurysm Progression

This repository contains pipelines and tools for single-cell RNA-sequencing (scRNA-seq) data analysis focused on aneurysm progression. It includes pre-processing, clustering, cell type annotation, differential gene expression analysis, trajectory inference, and pathway enrichment analysis.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Key Features](#key-features)
   - [Data Preprocessing](#data-preprocessing)
   - [Clustering and Cell Type Annotation](#clustering-and-cell-type-annotation)
   - [Differential Gene Expression Analysis](#differential-gene-expression-analysis)
   - [Trajectory Inference](#trajectory-inference)
   - [Pathway Enrichment Analysis](#pathway-enrichment-analysis)
5. [Visualization](#visualization)
6. [Dependencies](#dependencies)
7. [License](#license)

## Project Overview

This project explores aneurysm progression using single-cell RNA sequencing data from different mouse models. It includes:
- Integration of scRNA-seq data across multiple batches.
- Identification of distinct cell populations.
- Investigation of cell-specific pathways and molecular mechanisms.
- Reconstruction of differentiation trajectories.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YangxLab/single-cell-aneurysm.git
   cd single-cell-aneurysm
**# Single-Cell Analysis of Aortic Aneurysm (SCAA)

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
