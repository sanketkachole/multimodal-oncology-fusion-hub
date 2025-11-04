# 🧬 Multimodal-oncology-fusion-hub


> **A living map of multimodal learning in cancer — bridging pathology, radiology, genomics, and clinical data.**  
> Curated and maintained by researchers for the community.

![Awesome](https://awesome.re/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

---

## 🌍 Vision

Multimodal learning is transforming oncology — combining histopathology, omics, radiology, and clinical records to improve diagnosis, prognosis, and treatment selection.  
This repository tracks the **papers, datasets, codebases, and frameworks** driving that change.

> 🎯 *Goal:* Make multimodal cancer research reproducible, connected, and industry-ready.

---

## 📚 Table of Contents

- [Surveys & Reviews](#surveys--reviews)
- [Pathology + Genomics](#pathology--genomics)
- [Pathology + Clinical / Reports](#pathology--clinical--reports)
- [Radiology + Pathology](#radiology--pathology)
- [Survival / Prognosis Modeling](#survival--prognosis-modeling)
- [Foundation & Large Models](#foundation--large-models)
- [Datasets](#datasets)
- [Codebases](#codebases)
- [Companies & Labs](#companies--labs)
- [Contributing](#contributing)
- [License](#license)

---

## 🧭 Surveys & Reviews

| Year | Title | Venue | Link |
|------|--------|--------|------|
| 2024 | *From Classical ML to Emerging Foundation Models: Multimodal Data Integration for Cancer Research* | Information Fusion | [Paper](https://arxiv.org/abs/2404.XXXX) |
| 2023 | *Deep Multimodal Integration for Cancer Diagnosis and Prognosis* | IEEE Reviews | [Paper](https://doi.org/10.xxxx) |
| 2022 | *A Survey on Multimodal Learning in Digital Pathology* | Front. Oncol. | [Paper](https://doi.org/10.xxxx) |

---

## 🧫 Pathology + Genomics

| Year | Title | Cancer Type | Modalities | Dataset | Code |
|------|--------|--------------|-------------|---------|------|
| 2020 | *Pathomic Fusion: An Integrated Framework for Fusing Histopathology and Genomic Features for Cancer Diagnosis and Prognosis* | Brain, Kidney Cancer | histology image + genomic (mutations, CNV, RNA-Seq) | TCGA | [Code](https://github.com/mahmoodlab/PathomicFusion) | 
| 2025 | Robust Multimodal Survival Prediction with Conditional Latent Differentiation Variational AutoEncoder | pan-cancer | Generate Genomics from WSI | TCGA- (BLCA, BRCA, GBMLGG, LUAD, UCEC) | [Code](https://github.com/JJ-ZHOU-Code/RobustMultiModel) |
| 2025 | *Graph-based Fusion of WSI Tiles and RNA Expression for Survival Prediction* | Pan-Cancer | WSI + RNA | TCGA | [Code](https://github.com/example) |
| 2024 | *CLAM + RNAseq for MSI Prediction* | Colorectal | WSI + Mutation | CPTAC | – |
| 2023 | *Pathomic Fusion: Integrating Histology and Genomics* | Multi-cancer | WSI + Omics | TCGA | [Code](https://github.com/mahmoodlab/PathomicFusion) |

---

## 📄 Pathology + Clinical / Reports

| Year | Title | Cancer Type | Modalities | Dataset | Code |
|------|--------|--------------|-------------|---------|------|
| 2024 | *Slide2Report: Joint Modeling of WSIs and Pathology Reports* | Breast | WSI + Text | Institutional | – |
| 2023 | *Multimodal Prognosis with Clinical Notes and WSIs* | Lung | WSI + EHR | TCGA-LUAD | – |

---

## 🩻 Radiology + Pathology

| Year | Title | Cancer Type | Modalities | Dataset | Code |
|------|--------|--------------|-------------|---------|------|
| 2025 | *Cross-modal Matching of MRI and Histology for Glioma* | Brain | MRI + WSI | BraTS + local | – |
| 2023 | *CT-Path Fusion for Tumor Grade Prediction* | Liver | CT + WSI | Internal | – |

---

## ⏱ Survival / Prognosis Modeling

| Year | Title | Modalities | Cancer Type | Code |
|------|---------|--------------|--------------|------|
| 2025 | *HONeYBEE: Harmonized Oncology Multimodal Foundation Model* | Clinical + Path + Omics | Multi-cancer | [Paper](https://www.nature.com/articles/s41746-025-01016-x) |
| 2024 | *Deep Multimodal Survival Analysis on TCGA* | WSI + RNA + Clinical | Pan-Cancer | – |

---

## 🧠 Foundation & Large Models

| Model | Year | Modalities | Description | Code |
|--------|------|-------------|--------------|------|
| PLIP | 2023 | Vision–Language | Pathology foundation model (Paige) | [Code](https://github.com/paige-ai/PLIP) |
| MedCLIP | 2023 | Vision–Text | CLIP adapted to medical images | [Code](https://github.com/medclip) |
| Onco-FM | 2025 | Multimodal | Cancer-specific foundation model (path+omics+clinical) | – |

---

## 🧪 Datasets

| Name | Modalities | Cancer Types | Notes | Link |
|------|-------------|---------------|-------|------|
| **TCGA** | WSI, RNA, CNV, Clinical | 33 | Core multimodal resource | [Link](https://portal.gdc.cancer.gov) |
| **CPTAC** | Proteomics, WSI, Clinical | 10 | Quantitative proteomics + imaging | [Link](https://proteomics.cancer.gov) |
| **PANDA** | WSI, Gleason labels | Prostate | 10k slides for grading | [Link](https://www.kaggle.com/c/prostate-cancer-grade-assessment) |
| **Camelyon16/17** | WSI | Breast | Metastasis detection | [Link](https://camelyon17.grand-challenge.org) |

---

## 🧰 Codebases

| Project | Year | Description | Link |
|----------|------|--------------|------|
| **Pathomic Fusion** | 2020 | Early multimodal pathology+genomics fusion framework | [GitHub](https://github.com/mahmoodlab/PathomicFusion) |
| **HONeYBEE** | 2025 | Foundation model integrating pathology, omics, and clinical | [Paper](https://www.nature.com/articles/s41746-025-01016-x) |
| **PathOmics** | 2023 | Graph fusion of WSI + omics | [GitHub](https://github.com/Cassie07/PathOmics) |

---

## 🏢 Companies & Labs

| Name | Focus | Modality Scope |
|------|--------|----------------|
| **Owkin** | Multimodal oncology AI (WSI + omics + clinical) |
| **Tempus** | Precision oncology with multimodal patient data |
| **Paige AI** | Foundation models for pathology |
| **Mahmood Lab (Harvard)** | Pathology + genomics fusion |
| **Kather Lab (NCT Heidelberg)** | Computational pathology + multi-omics |
| **Gevaert Lab (Stanford)** | Integrative cancer omics |

---

## 🤝 Contributing

Contributions are welcome!

1. **Fork** the repo and make a branch.  
2. Add your paper, dataset, or code using this format:

```text
Title:
Year:
Cancer type:
Modalities:
Dataset:
Link:
