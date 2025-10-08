# Predictive Modeling of Wind Turbine Power Output Using SCADA Data

This repository contains the full implementation, experiments, and analysis code for the paper:

> **"Predictive Modeling of Wind Turbine Power Output Using SCADA Data"**  
> Md. Rakin-Al-Mahin, 2025  
> [Department of Computer Science and Engineering, RUET]  
> [rakinalmahin@gmail.com]

> _(research project submission)_

---

## 📘 Overview

This project presents a **data-driven regression framework** for predicting the active power output (kW) of wind turbines using publicly available **SCADA datasets**.  
The approach combines **domain-aware feature engineering** and **interpretable machine learning models** to achieve high prediction accuracy with limited-frequency (10-minute) SCADA data.

**Highlights**

- Extensive data preprocessing and EDA pipeline
- Polynomial, lag, and rolling feature engineering
- Baseline and advanced regression models (Linear, Ridge, Random Forest, MLP, XGBoost, etc.)
- Rigorous evaluation using bootstrapping and statistical tests
- Comprehensive ablation study demonstrating feature contributions

---

## 📊 Dataset

- **Source:** [Kaggle – Wind Turbine SCADA Dataset](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset/data)
- **Size:** ~50,530 samples, 6 columns
- **Sampling Rate:** 10-minute intervals
- **Main Features:**
  - `Wind Speed (m/s)`
  - `Wind Direction (°)`
  - `Theoretical_Power_Curve (kWh)`
  - `LV ActivePower (kW)` _(target)_
  - Derived temporal and polynomial features

---
