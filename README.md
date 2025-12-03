# Project Description

This repository contains the analysis, clustering, and predictive models developed using the dataset found on [Kaggle](https://www.kaggle.com/datasets/dataregina/datasets-para-proyecto-bi?select=categorias.csv).

## Repository Structure

The project is organized into the following directories:

- **`data_clean`**: Contains the cleaned and processed CSV files, aggregated for analysis.
- **`data_raw`**: Original raw data downloaded directly from Kaggle.
- **`notebooks`**: Jupyter notebooks containing the entire data science pipeline:
    - `Cleaning_EDA.ipynb`: Data cleaning and Exploratory Data Analysis (EDA), featuring detailed comments and interactive visualizations using **Plotly**.
    - `Clustering.ipynb`: Implementation of clustering algorithms, including the methodology and justification for selecting the optimal number of clusters.
    - `model.ipynb`: Development, training, and evaluation of predictive models.



# 📦 Project Setup Instructions

Follow these steps to set up the project locally and run the code.

---

## 1. Clone the Repository
```bash
git clone https://github.com/Polito9/Sales-Pattern-Analysis.git
cd Sales-Pattern-Analysis
```

## 2. Install Project Dependencies
All required packages are listed in requirements.txt, it is recommended to install them in a virtual enviroment.

```bash
pip install -r requirements.txt
```

Now you can run all notebooks without problems


## Updating Dependencies (for contributors)

If you install or update packages, regenerate requirements.txt after installing a package.

```bash
pip freeze > requirements.txt
```
