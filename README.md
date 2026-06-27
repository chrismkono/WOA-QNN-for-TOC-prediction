# Hybrid WOA-QNN Framework for Multi-Well TOC Prediction

[!\[License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the official production-ready implementation of the hybrid **Whale Optimization Algorithm - Quantum Neural Network (WOA-QNN)** model for continuous Total Organic Carbon (TOC) estimation using wireline log suites. The framework is benchmarked against state-of-the-art classical models (CatBoost) and standalone QNN with gradient descent Parameterized Quantum Circuits (PQCs) to validate predictive robustness in complex multi-well basin environments.

\---

## 📌 Repository Structure

```text
├── .gitignore          <- System files to ignore in Git tracking
├── LICENSE             <- MIT open-source license agreement
├── README.md           <- Repository setup and execution guide
├── requirements.txt    <- Complete Python package dependencies
└── notebooks/
    └── WOAQNN\_TOC.ipynb  <- Integrated Jupyter Notebook containing all 3 models

