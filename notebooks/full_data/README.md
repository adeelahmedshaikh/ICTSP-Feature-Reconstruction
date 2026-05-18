# Full-Data Forecasting Experiments

This directory contains the full-data forecasting experiments conducted using the ICTSP framework.

## Description

The experiments evaluate the effect of reconstruction-based preprocessing on forecasting performance when the complete training dataset is available.

The following preprocessing methods are compared:

- Baseline ICTSP
- STL Reconstruction
- Wavelet Reconstruction
- Singular Spectrum Analysis (SSA)

## Forecast Horizons

Experiments were conducted using:
- Prediction length = 96
- Prediction length = 192

## Datasets

The experiments include:
- ETTh1
- ETTh2
- ETTm1
- ETTm2
- Exchange
- Weather

## Evaluation Metrics

Performance is evaluated using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

## Notes

All experiments preserve:
- identical ICTSP architecture
- identical training configuration
- identical dataset splits

Only the preprocessing stage differs between methods.
