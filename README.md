<div>
  
<p align="center">
  <img src="images/DataSphere AI_ Predict, Segment, Forecast.png" alt="DataSphere AI Banner" width="100%">
</p>

</div>

# DataSphere AI

### Applied Machine Learning & Predictive Analytics

DataSphere AI is a collection of practical Data Science and Machine
Learning projects covering supervised learning, unsupervised learning,
model explainability, customer segmentation, and time-series
forecasting.

The repository contains three Jupyter Notebook projects that demonstrate
different approaches to extracting insights and making predictions from
structured data.

## Projects

### 1. Bank Marketing Prediction

**Notebook:** `Task_1.ipynb`

A binary classification project that predicts the target variable
`deposit` using a bank marketing dataset.

**What it covers** - Dataset inspection and exploratory data analysis -
Missing-value checks and categorical encoding - Feature scaling with
`StandardScaler` - Train-test split - Model training with Random Forest
and Logistic Regression - Evaluation using confusion matrices, F1
scores, and ROC curves - Model explainability using LIME

**Main libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn,
LIME

### 2. Mall Customer Segmentation

**Notebook:** `Task_2.ipynb`

An unsupervised learning project that groups mall customers based on
annual income and spending score.

**What it covers** - Dataset inspection and exploratory data analysis -
Customer demographic and spending visualizations - Correlation heatmap -
K-Means clustering - Elbow method using within-cluster sum of squares
(WCSS) - PCA-based two-dimensional cluster visualization

**Main libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### 3. Household Energy Consumption Forecasting

**Notebook:** `Task_3 (1).ipynb`

A time-series forecasting project that analyzes household electricity
consumption and compares forecasting models.

**What it covers** - Data inspection and missing-value handling - Date
and time processing - Hourly resampling of global active power -
Time-based feature engineering (hour, weekday, and weekend indicator) -
Chronological train-test split - Forecasting with ARIMA, Prophet, and
XGBoost - Model comparison using Root Mean Squared Error (RMSE) -
Actual-versus-forecast visualization

**Main libraries:** Pandas, NumPy, Matplotlib, Statsmodels, Prophet,
XGBoost, Scikit-learn

## Tech Stack

-   **Language:** Python
-   **Environment:** Jupyter Notebook
-   **Data processing:** Pandas, NumPy
-   **Visualization:** Matplotlib, Seaborn
-   **Machine Learning:** Scikit-learn
-   **Model explainability:** LIME
-   **Time-series forecasting:** Statsmodels (ARIMA), Prophet, XGBoost

## Repository Structure

``` text
DataSphere-AI/
│
├── Task_1.ipynb
├── Task_2.ipynb
├── Task_3 (1).ipynb
├── bank.csv
├── Mall_Customers.csv
├── household_power_consumption.csv
├── requirements.txt
└── README.md
```

The CSV files are the datasets referenced by the notebooks. Add the
corresponding dataset files to the repository or update the notebook
paths if your files are stored elsewhere.

## Getting Started

### 1. Clone the repository

``` bash
git clone <your-repository-url>
cd DataSphere-AI
```

### 2. Create and activate a virtual environment (recommended)

``` bash
python -m venv .venv
```

Windows:

``` bash
.venv\Scripts\activate
```

macOS / Linux:

``` bash
source .venv/bin/activate
```

### 3. Install dependencies

``` bash
pip install -r requirements.txt
```

If you do not have a `requirements.txt` file yet, install the libraries
used in the notebooks:

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn lime statsmodels prophet xgboost jupyter
```

### 4. Launch Jupyter Notebook

``` bash
jupyter notebook
```

Open the notebook you want to explore and run its cells in order. Make
sure its required CSV dataset is available at the path specified in the
notebook.

## Evaluation Metrics and Methods

  -----------------------------------------------------------------------
  Project                 Methods / Models        Evaluation or analysis
  ----------------------- ----------------------- -----------------------
  Bank Marketing          Random Forest, Logistic Confusion matrix, F1
  Prediction              Regression              score, ROC curve

  Mall Customer           K-Means, PCA            WCSS / Elbow method,
  Segmentation                                    cluster visualization

  Energy Consumption      ARIMA, Prophet, XGBoost RMSE, actual
  Forecasting                                     vs. forecast plot
  -----------------------------------------------------------------------

## Learning Objectives

Through these projects, the repository demonstrates practical experience
with:

-   Data cleaning and preprocessing
-   Exploratory Data Analysis (EDA)
-   Feature engineering and feature scaling
-   Supervised classification
-   Unsupervised clustering
-   Dimensionality reduction
-   Time-series forecasting
-   Model evaluation and comparison
-   Interpretable machine learning

## Notes

-   The notebooks expect the CSV datasets to be available locally.
-   Model results depend on the dataset and execution environment.
-   The notebooks should be run from top to bottom so that variables and
    preprocessing steps are initialized correctly.
-   This repository documents the workflows implemented in the
    notebooks; it does not claim production deployment or a particular
    model accuracy.


If you find this project collection useful, consider giving the
repository a ⭐ on GitHub.
