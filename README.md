# traffic-aware-5g-energy-forecasting

Traffic-Aware, Interpretable Energy Forecasting for 5G Base Stations

Hybrid TA-GRU/XGBoost framework with SHAP explainability for interpretable 5G base station energy forecasting.

Research Project

Overview

This repository contains the complete implementation of our research on interpretable energy forecasting for 5G base stations.

The entire pipeline—from dataset loading to model training, evaluation, explainability analysis, statistical testing, and figure generation—is implemented in a single reproducible Python script, making it easy to reproduce all experiments from the paper.

Features
End-to-end reproducible pipeline
Automatic dataset download
Feature engineering
TA-GRU model
XGBoost baseline
Hybrid ensemble
SHAP explainability
Temporal attention visualization
Statistical significance testing
Publication-quality figures
CSV result tables
Repository
green_5g_pipeline_v3.py

The script performs:

Dataset download
Feature engineering
Data preprocessing
Sequence generation
Baseline model training
TA-GRU training
XGBoost training
Hybrid ensemble creation
SHAP analysis
Attention visualization
Ablation study
Diebold–Mariano significance testing
Figure generation
Results table generation
Dataset

The project uses the ITU 5G Base Station Energy Consumption Dataset.

92,629 hourly samples
921 real base stations
Energy consumption
Traffic load
Energy Saving Mode
Transmit power

The dataset is automatically downloaded by the script using KaggleHub.



The script automatically:

downloads the dataset
trains every model
generates all figures
exports result tables
performs explainability analysis
Outputs

The pipeline generates:

EDA plots
Correlation heatmap
Training curves
Model comparison plots
Attention visualization
SHAP explanations
Prediction vs Actual graphs
Error analysis
CSV tables
Statistical significance results
Models Implemented
Persistence
Ridge Regression
LSTM
GRU
XGBoost
Temporal Attention-GRU
Hybrid TA-GRU + XGBoost

The paper has been accepted for publication at IEEE TEMSCON ASPAC 2026.
Full citation, DOI, and IEEE Xplore link will be added once the proceedings are published.
