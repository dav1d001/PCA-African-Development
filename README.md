# PCA on African Development Indicators

## Overview
This project implements Principal Component Analysis (PCA) from scratch using NumPy and Pandas. It analyzes World Bank development data from Sub-Saharan African countries to reduce dimensionality while retaining 95% of the variance.

## Contents
* `PCA_Analysis.ipynb`: The main notebook containing the implementation, visualization, and analysis.
* `africa_data.csv`: The raw dataset sourced from World Bank Indicators (2022).
* `requirements.txt`: List of Python dependencies.

## Key Findings
* The analysis successfully reduced **39 original indicators** down to **9 Principal Components**.
* These 9 components capture **95.3%** of the information in the dataset.
* Visualizations (Scree Plot, Correlation Heatmap, and PCA Scatter) are included in the notebook.

## How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
