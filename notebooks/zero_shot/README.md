# Zero-Shot Transfer Experiments

This directory contains zero-shot transfer forecasting experiments using the ICTSP framework.

## Description

The experiments evaluate the transferability of contextual representations across:
- datasets
- domains
- temporal resolutions

without retraining on the target dataset.

## Transfer Directions

Examples include:
- ETTh1 → ETTh2
- ETTh2 → ETTh1
- ETTm1 → ETTm2
- ETTm2 → ETTm1
- ETTh1 → ETTm1
- ETTm1 → ETTh1
- Exchange → Weather
- Weather → Exchange

## Reconstruction Methods

The following methods are compared:
- Baseline ICTSP
- STL Reconstruction
- Wavelet Reconstruction
- Singular Spectrum Analysis (SSA)

## Evaluation Metrics

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
