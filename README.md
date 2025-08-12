# EEG Motion Imaginary – Biosignal Acquisition and Processing

Course assignment for **Biosignal Acquisition and Processing** (NTUA, 2024–2025), analyzing EEG data from a motor imagery experiment.

## Overview
- Two conditions: **Both** (imagined movement with both hands) and **None** (rest).
- Preprocessing: FIR Butterworth filter (1–35 Hz), baseline removal, detrending.
- Feature extraction: PSD, kurtosis, skewness, mean, variance across frequency bands.
- Statistical validation: One-Way ANOVA between conditions.

## Files
- `EEG_Motion_Imaginary.ipynb`: Full analysis notebook.

## Tools
Python, NumPy, pandas, SciPy, matplotlib, mne.
