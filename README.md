# Prostate_Cancer_Autoencoder
Concordance Index Guided Autoencoder-Based Feature Extraction Using RNA-Seq Data Unveils Master Regulators For High-Risk Prostate Cancer Patients

## Overview

This repository contains the complete analysis pipeline for prostate cancer prognosis prediction using RNA-Seq Data.

## Methods

- Autoencoder-based Feature Extraction
- Cox Proportional Hazards Modeling
- Risk Stratification and Survival Analysis
- Differential Gene Expression Analysis
- Functional Enrichment Analysis
- Transcription Factor Analysis

## Requirements

```bash
pip install -r requirements.txt
```

## Dataset

The study uses publicly available TCGA-PRAD datasets obtained from the UCSC Xena repository.

### Datasets Used

- TCGA-PRAD Gene Expression Dataset (HiSeqV2)
- TCGA-PRAD Clinical Dataset

### Data Availability

The datasets analyzed in this study are publicly available through the UCSC Xena platform:

https://xenabrowser.net/

The dataset download links are included in the notebook.

## Usage

Open and run:

```text
Prostate_Cancer_Prognosis.ipynb
```

## Code Availability

The complete source code and analysis pipeline are available in this repository.

## Supplementary Material

Additional figures supporting the results presented in the manuscript are available in the `supplementary/` directory.

- Figure S1: Gene variance distribution in the PRAD dataset. The dashed line indicates the selected variance threshold (1.0)
- Figure S2: Training and validation loss curves of the autoencoder model
- Figure S3: Silhouette analysis indicating K = 2 as the optimal number of clusters
- Figure S4: GO biological process enrichment analysis of significant differentially expressed genes

## Citation

If you use this code, please cite the associated publication.
