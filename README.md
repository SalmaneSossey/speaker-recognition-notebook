# Speaker Recognition Notebook

A simple speaker recognition prototype using synthetic sine-wave audio to demonstrate the full pipeline: preprocessing, feature extraction (MFCCs and spectral stats), modeling, and evaluation.

## Contents
- `speaker_recognition_notebook.ipynb` — end-to-end workflow with code and explanations.

## Quick Start
1) Open the notebook in Jupyter/Lab.
2) Run all cells; the notebook generates synthetic data, trains a classifier, and reports metrics.

## Notes
- Uses synthetic signals so it runs quickly without external datasets.
- Includes preprocessing (normalization, silence trimming), MFCC-based features with deltas, and a linear SVM baseline.
