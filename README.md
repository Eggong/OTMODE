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




📖 Read our paper (coming soon) | 🔬 Built with Python & scRNA-seq in mind

---

## 🚀 Installation

```bash
pip install git+https://github.com/Eggong/OTMODE.git
