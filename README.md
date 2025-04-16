# Regime Detection via Hurst Exponent Estimation

This project explores market regime detection using Hurst exponent methods, including rolling window estimations and wavelet transforms. Using an approximation of the Hurst exponent to define market periods is quick and intiutive, but not as accurate as other methods.

## Features
- Rolling Hurst estimation
- Wavelet-based Hurst estimation
- Regime classification based on Hurst thresholds
- Using BIC to inform the number of Regimes to include

## Visualizations
<p align="center">
  <img src="notebooks/example_regime_plot.png" width="600">
</p>

## How to Run
```bash
pip install -r requirements.txt
python src/regime_detector.py
