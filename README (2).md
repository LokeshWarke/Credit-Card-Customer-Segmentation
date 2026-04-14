# Credit Card Customer Segmentation

## Project Overview
This project performs customer segmentation for a credit card company using K-Means clustering. The analysis groups customers into segments to inform targeted business strategies.

## Dataset
- `customer_segmentation.csv` — dataset used for the analysis (10,127 rows, 14 columns). The dataset contains customer demographics, account and transaction metrics.

## Notebook
The full analysis and visualizations are in the notebook: [Mission745Solutions.ipynb](Mission745Solutions.ipynb).

## Methodology
- Exploratory Data Analysis (EDA) to understand distributions and correlations.
- Feature engineering for categorical columns (`gender`, `education_level`, `marital_status`).
- Standardization of numeric features using `StandardScaler`.
- K-Means clustering; elbow method used to choose number of clusters (K=6).
- Cluster profiling with numeric summaries and categorical distributions.

## Key Findings (summary)
- Six customer clusters were identified with distinct characteristics (e.g., high spenders, low-income high-utilization customers, older long-term customers, etc.).
- Cluster-level insights and potential business actions are described in the notebook.

## Files in this repo
- `Mission745Solutions.ipynb` — Jupyter notebook with the full analysis.
- `customer_segmentation.csv` — source dataset.
- `README.md` — this file.

## Requirements
Install the main dependencies used in the notebook:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

Optional: use a virtual environment or conda environment for reproducibility.

## How to run
1. Ensure `customer_segmentation.csv` and `Mission745Solutions.ipynb` are in the same folder as this README.
2. Start Jupyter Notebook or JupyterLab:

```
jupyter notebook Mission745Solutions.ipynb
```

3. Run the notebook cells in order. The notebook handles data loading, preprocessing, clustering, and visualization.

## Next steps and improvements
- Create a `requirements.txt` or `environment.yml` for reproducible environments.
- Add a script to export cluster assignments to CSV for downstream use.
- Experiment with other clustering algorithms (DBSCAN, Gaussian Mixture Models) and dimensionality reduction for visualization.

## Author
Prepared as a guided project for credit card customer segmentation. For questions or follow-ups, update the notebook or open an issue in this repository.
