# Multivariate Anomaly Detection for Memory Leak Identification

## Overview
This project focuses on detecting memory leak patterns in software systems
using multivariate anomaly detection on system-level metrics collected
over time.

The goal is to identify abnormal behaviour that cannot be captured by
single-metric thresholding approaches.

## Context
This work is based on my MSc practicum at Dublin City University and has
been restructured here as a clean, professional portfolio project.

## Objectives
- Analyse multivariate time-series system metrics
- Detect anomalous patterns indicating potential memory leaks
- Compare different anomaly detection approaches

## Status
Project setup in progress. Documentation and structure completed first,
followed by model implementation and evaluation.

## Repository Structure
- `data/` – Datasets and processed data used for analysis
- `notebooks/` – Exploratory analysis and experimentation notebooks
- `src/` – Reusable source code for models and utilities
- `results/` – Outputs, visualisations, and evaluation results

## Data Description
The analysis is based on system-level metrics collected over time from a
running application. These metrics reflect memory usage behaviour and
related resource indicators.

Typical metrics include memory consumption patterns and other correlated
signals that help identify abnormal behaviour associated with memory leaks.

