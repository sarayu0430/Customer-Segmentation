# Customer Segmentation (Clustering)

This repository contains an interactive Jupyter notebook implementing customer segmentation (clustering) using the provided marketing dataset.

**Contents**
- Notebook: [Customer Segmentation (Clustering).ipynb](Customer%20Segmentation%20(Clustering).ipynb)
- Dataset: [marketing_campaign.csv](marketing_campaign.csv)
- This README: [README.md](README.md)

**Overview**
- Purpose: Demonstrate customer segmentation using clustering techniques (e.g., K-Means clustering) to identify customer groups for targeted marketing.
- Input data: `marketing_campaign.csv` (cleaning and feature engineering are performed in the notebook).

**Requirements**
# Customer Segmentation (Clustering)

This repository demonstrates customer segmentation using clustering techniques on the provided marketing dataset. The analysis is implemented as an interactive Jupyter notebook that covers exploratory data analysis, preprocessing, clustering, evaluation, and visualizations.

**Contents**
- Notebook: [Customer Segmentation (Clustering).ipynb](Customer%20Segmentation%20(Clustering).ipynb)
- Dataset: [marketing_campaign.csv](marketing_campaign.csv)
- This README: [README.md](README.md)

**Quick start**
1. (Recommended) Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1   # PowerShell
```

2. Install required packages:

```powershell
pip install pandas numpy scikit-learn matplotlib seaborn scipy jupyterlab
```

3. Launch Jupyter and open the notebook:

```powershell
jupyter lab
# or
jupyter notebook
```

4. Open [Customer Segmentation (Clustering).ipynb](Customer%20Segmentation%20(Clustering).ipynb) and run the cells in order.

**Dataset**
- The notebook reads `marketing_campaign.csv` from the repository root. Ensure the file remains next to the notebook.
- The notebook performs basic cleaning and feature engineering before applying clustering algorithms.

**What you'll find in the notebook**
- Data loading and exploratory data analysis (EDA).
- Data cleaning and feature engineering.
- Clustering (e.g., K-Means) and cluster evaluation.
- Visualizations to interpret cluster characteristics.

**Reproducibility**
- Set random seeds in clustering steps to reproduce results (see code comments in the notebook).

