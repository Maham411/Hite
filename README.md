# CSX-Net

Reproduction code and experiment outputs for the paper:  
**"CSX-Net: A Hybrid CNN–Self-Attention-LSTM–XGBoost Ensemble for Robust Per-Class Intrusion Detection in Digital Twin-Enabled IoT Networks"**

## Overview
- **Dataset:** N-BaIoT (UCI Machine Learning Repository, Dataset 442 — 9 IoT devices, 9 traffic classes)
- **Architecture:** 1D-CNN + Self-Attention LSTM (SALSTM) branches stacked via an XGBoost meta-learner
- **Experiments:** 5-fold out-of-fold (OOF) stacking, duplicate-free evaluation, ablation studies, and statistical significance testing (McNemar's test)

## Usage
Open `CSX_Net_reproduction.ipynb` in Google Colab with a GPU runtime (T4) and run the sections sequentially.
