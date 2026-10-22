# Bike Rental Demand Prediction

## About the project

This project predicts hourly bike rental demand using historical bike-sharing data. The notebook covers data preparation, exploratory analysis, regression model training, evaluation, and feature-importance analysis.

## Dataset

The project uses the UCI Bike Sharing hourly dataset, with 17,379 records covering 2011–2012. The notebook downloads the dataset automatically from the UCI repository if the local data file is not available. An internet connection is required for the first run.

## Files in this repository

* `Bike\_Rental\_Demand\_Prediction.ipynb` — the main notebook containing the analysis and machine learning workflow.
* `requirements.txt` — Python package dependencies.
* `README.md` — project overview and run instructions.

## Main chronological test results

The notebook's recorded primary evaluation uses training data through 2012-08-06 and test data beginning 2012-08-07.

|Model|MAE|RMSE|R²|
|-|-:|-:|-:|
|HistGradientBoosting|41.973|64.513|0.914|
|Random Forest|56.037|83.916|0.855|
|Linear Regression|98.871|133.838|0.632|

MAE and RMSE are measured in rental counts. These are the results recorded in the project notebook; run all cells to verify them in your environment.

## How to run

1. Install Python 3.10 or newer.
2. Download or clone this repository.
3. In the project directory, install dependencies:

```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook or JupyterLab:

```bash
   jupyter notebook
   ```

5. Open `Bike\_Rental\_Demand\_Prediction.ipynb` and run all cells from top to bottom.

The first run requires internet access to download the dataset.

## 

