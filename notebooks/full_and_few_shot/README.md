# Full-Data and Few-Shot Experiments

This directory contains the ICTSP experiments performed under:

- Full-data forecasting
- Few-shot 10% forecasting
- Few-shot 5% forecasting

## Reconstruction Methods

The experiments compare:

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

## Notes

All experiments preserve:
- identical ICTSP architecture
- identical training configuration
- identical evaluation metrics

Only the preprocessing stage differs across methods.
