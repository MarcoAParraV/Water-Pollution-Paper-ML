# Adapted Objective Index of Water Pollution: A Transferable ML Approach

This repository contains the complete reproducible notebook for the paper **“Adapted Objective Index of Water Pollution: A Transferable ML Approach.”**

The project proposes an adapted Objective Index of Pollution (`OIP_adapted`) for water-quality assessment using commonly available physicochemical and microbiological parameters. The framework is first constructed and validated using Indian river water-quality observations, and then transferred to a harmonized Mexican water-quality dataset from CONAGUA’s RENAMECA monitoring network.

## Overview

The main goal of this project is to evaluate whether an interpretable rule-based pollution index can be combined with machine learning to support cross-domain water-quality assessment.

The pipeline includes:

- Construction of an adapted Objective Index of Pollution (`OIP_adapted`)
- Cleaning and preprocessing of real-world water-quality data
- Classification of water pollution levels into severity categories
- Benchmarking of multiple supervised machine learning models
- Hyperparameter tuning of selected classifiers
- Continuous surrogate modeling using Random Forest regression
- Harmonization of Mexican RENAMECA data into the Indian feature schema
- India-to-Mexico transfer evaluation
- Basin-level transfer analysis for selected Mexican river systems
- Generation of descriptive tables, metrics, and figures used in the paper

## Repository Structure

```text
.
├── River-Pollution_ML-Project_EntregaFinal_with_Table2.ipynb
├── data/
│   └── raw/
│       ├── water_dataX.csv
│       └── renameca-lotico.xlsx
└── README.md
