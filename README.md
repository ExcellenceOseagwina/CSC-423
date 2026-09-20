# CSC 423: Machine Learning Coursework

This repository contains a collection of machine learning exercises and practicals completed as part of CSC 423, covering both supervised and unsupervised learning techniques. The work focuses on house price prediction, fraud detection, clustering, dimensionality reduction, image analysis, and model evaluation.

## Overview

The coursework includes:

- House price prediction using regression
- Fraud detection with Gaussian Mixture Models (GMM)
- K-Means clustering and customer segmentation
- Gaussian Mixture Model comparison and BIC analysis
- Principal Component Analysis (PCA) and dimensionality reduction
- Digit analysis and visualization of image data
- Model evaluation and visualization of learned patterns

## Repository Structure

- `Oseagwina_COSC22404_Ass2.ipynb` — main assignment notebook for machine learning tasks
- `unsupervised_learning_practical.ipynb` — practical exercises on clustering and unsupervised learning
- `house_prediction_app.py` — small local web app for predicting house prices
- `run_house_prediction_app.bat` — Windows helper script to launch the prediction app
- `README_HOUSE_PREDICTION_DEPLOYMENT.md` — deployment and usage guide for the prediction app
- `*.png` files — visual outputs such as clustering plots, PCA graphs, and GMM results
- `Oseagwina_COSC22404_Ass1.pdf` and `Oseagwina_COSC22404_Ass2.pdf` — assignment submissions in PDF form

## Main Topics Covered

### 1. House Price Prediction
A regression-based model is used to estimate median house values from California housing features such as:

- Median income
- House age
- Average rooms
- Average bedrooms
- Population
- Average occupants
- Latitude
- Longitude

The repository includes a lightweight app for local prediction and experimentation.

### 2. Fraud Detection with GMM
The project explores unsupervised anomaly detection using Gaussian Mixture Models to identify suspicious or anomalous patterns in transactional data.

### 3. Clustering and Customer Segmentation
K-Means and Gaussian Mixture Models are used to group data into meaningful clusters and evaluate segmentation quality.

### 4. PCA and Dimensionality Reduction
Principal Component Analysis is applied to reduce dimensionality and visualize data relationships, especially in the digits dataset.

### 5. Digital Image Analysis
The notebooks demonstrate how ML methods can be applied to handwritten digit data, including visual inspection and feature reduction.

## Getting Started

### Prerequisites

- Python 3.9+ recommended
- Jupyter Notebook or JupyterLab
- Common scientific libraries such as:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn`

You can install the requirements with:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn jupyter
```

### Launch Jupyter

```bash
jupyter notebook
```

Then open the relevant notebook from the repository root.

## Running the House Prediction App

From the repository root:

```bash
python house_prediction_app.py
```

Then open:

```text
http://127.0.0.1:8000
```

On Windows, you can also run:

```powershell
run_house_prediction_app.bat
```

## Notes

This repository is primarily coursework-oriented and contains notebooks, generated plots, and supporting scripts used to explore and explain machine learning concepts. It is best viewed as a practical lab archive demonstrating core ML techniques.

## Suggested Next Steps

- Open the notebook files in Jupyter to review the full experiments and code
- Use the house prediction app to interact with the regression model
- Explore the generated visual outputs for clustering, PCA, and GMM behavior
- Extend the analysis with your own preprocessing, model tuning, or evaluation metrics

## License

No explicit license file is included in this repository. Please check with the repository owner before reusing the code or materials for publication or commercial use.
