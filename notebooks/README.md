# Experiment Notebooks

This directory contains the Jupyter notebooks used for the ICTSP feature reconstruction experiments.

## Folder Structure

### full_data/
Contains experiments conducted using the complete training datasets under standard supervised forecasting settings.

### few_shot/
Contains experiments performed under limited-data settings using reduced training splits (10% and 5%).

### zero_shot/
Contains zero-shot transfer forecasting experiments across datasets and temporal resolutions.

## Reconstruction Methods

The notebooks evaluate the following preprocessing approaches:

- Baseline ICTSP
- STL Reconstruction
- Wavelet Reconstruction
- Singular Spectrum Analysis (SSA)

## Forecast Horizons

Experiments were primarily conducted using:
- Prediction length = 96
- Prediction length = 192

## Notes

The notebooks preserve the original ICTSP architecture and training configuration. Only the preprocessing stage changes between experiments.
