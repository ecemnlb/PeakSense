Peak Deconvolution App for AA, DA, and UA

This MATLAB app performs peak deconvolution of three analytes: Ascorbic Acid (AA), Dopamine (DA), and Uric Acid (UA) from voltammetric data. It includes baseline correction, peak detection, feature extraction, and machine learning-based concentration prediction using pre-trained models.

Features:

Interactive plotting of raw and baseline-corrected signals

ML-based prediction of peak positions, amplitudes, and variances

Estimation of AA, DA, and UA concentrations using trained regression models

User-friendly MATLAB App Designer interface

Import custom CSV data and analyze with one click

File Structure:

peakAnalysiss.mlapp → Main MATLAB App Designer application
trainedModel_conAA.mat → Pre-trained regression model for AA
trainedModel_conDA.mat → Pre-trained regression model for DA
trainedModel_conUA.mat → Pre-trained regression model for UA
README.txt (this file) → Overview and instructions

Getting Started:

Requirements:

MATLAB R2020a or newer

Statistics and Machine Learning Toolbox

Curve Fitting Toolbox (optional but recommended)

Installation:

Clone this repository:
git clone https://github.com/yourusername/peak-deconvolution-app.git
cd peak-deconvolution-app

Open MATLAB and navigate to the project directory.

Open the app file:
open('peakAnalysiss.mlapp')

Run the app from the App Designer or click "Run" in the toolbar.

Usage Instructions:

Click "Import" to load your voltammetry data (.csv file, two columns: potential and current).

Click "Analyze" to apply baseline correction, peak feature extraction, ML-based peak mapping, and concentration prediction.

View predicted concentrations for AA, DA, and UA in the "Predicted Concentrations" panel.
