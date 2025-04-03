<p align="center">
  <img src="https://github.com/Eggong/OTMODE/blob/main/figure/logo.png" height="150">
</p>

<p align="center">
  <strong>OTMODE: Optimal Transport-Based Framework for Differential Feature Identification in Single-Cell Multi-Omics</strong>
</p>

<p align="center">
  <a href="https://github.com/Eggong/OTMODE/actions">
    <img src="https://img.shields.io/github/workflow/status/Eggong/OTMODE/CI?label=build" alt="Build Status">
  </a>
  <a href="https://github.com/Eggong/OTMODE/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Eggong/OTMODE" alt="License">
  </a>
  <a href="https://pypi.org/project/otmode/">
    <img src="https://img.shields.io/pypi/v/otmode?color=brightgreen&label=pypi" alt="PyPI version">
  </a>
  <img src="https://img.shields.io/pypi/pyversions/otmode" alt="Python Versions">
</p>

---
## 🧬 Overview

**OTMODE** is a computational framework built on **Optimal Transport (OT)** theory for improving cell-type annotation accuracy and for identifying **differential features** across conditions in **single-cell multi-omics** data.

It provides interpretable metrics, including **Sinkhorn distances**, to compare cell types and clusters across predicted and true annotations. Please see our architecture of the OTMODE framework for more details!

<p align="center">
  <img src="https://github.com/Eggong/OTMODE/blob/main/figure/OTMODE_Schmatic.png" alt="OTMODE Architecture" width="900"/>
</p>


To optimize the performance of OTMODE in differential feature detection, we evaluated its behavior under various parameter settings. Our results showed that parameter values between 0.1 and 1.0 generally yielded the highest performance.

<p align="center">
  <img src="https://github.com/Eggong/OTMODE/blob/main/figure/Parameter_Tuning_Benchmarking.png" alt="OTMODE Architecture" width="900"/>
</p>

🔬 Built with Python

---

## 📘 Tutorials

We provide interactive tutorials to help users get started with applying **OTMODE** to multi-omics single-cell data. These tutorials demonstrate real use cases such as cell type annotation and differential feature detection.

All tutorials are provided as Jupyter notebooks and are located in the [`tutorials/`](./tutorials) folder.

### 🧪 Available Tutorials

| Tutorial | Description | Link |
|----------|-------------|------|
| **Application 1: Cell Type Annotation** | Learn how to use OTMODE to annotate cell types using integrated multi-omics data. | [View Notebook ›](./tutorials/OTMODE_App1_Tutorial.ipynb) |
| **Application 2: Differential Feature Detection** | Step-by-step guide to detect differentially expressed genes or features across cell groups. | [View Notebook ›](./tutorials/OTMODE_App2_Tutorial.ipynb) |

---

### 📝 Notes for Users

Each tutorial is **fully commented** and includes the following steps:

- 📂 **Data Loading and Preparation**  
  Load example or user-provided multi-omics data and prepare it for analysis.

- ⚙️ **Application of the OTMODE Algorithm**  
  Apply the OTMODE method to integrate modalities and infer latent representations.

- 📊 **Visualization of Results**  
  Generate plots such as **UMAP**, **heatmaps**, and **feature importance** to interpret results.

- 🔍 **Interpretation of Outputs**  
  Understand clustering, annotations, or differential features identified by OTMODE.

---

> ✅ **Recommended Environment**  
> - Python **≥ 3.8**  
> - Libraries: `scanpy`, `anndata`, `numpy`, `matplotlib`, `seaborn`, and others listed in `requirements.txt`


---
