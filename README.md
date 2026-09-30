# Mobile Price Prediction

## Overview

This project analyzes mobile phone specifications and predicts the corresponding price range using machine learning.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, data visualization, model training, and model evaluation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Dataset

The dataset contains mobile phone specifications such as battery power, RAM, internal memory, screen dimensions, pixel resolution, and camera specifications along with the corresponding price range.

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Visualization
6. Model Training
7. Model Evaluation

## Feature Engineering

The following features were created during the analysis:

- Screen Area
- Pixel Density
- Memory Power
- Performance Score
- Battery-to-Weight Ratio
- Total Camera

## Machine Learning Model

### Random Forest Classifier

A Random Forest Classifier was used to classify mobile phones into different price ranges based on their specifications.

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Project Files

- `Mobile_Price_Prediction.ipynb` – Contains the complete data analysis, feature engineering, visualization, model training, and evaluation workflow.
- `Mobile_Price_Range_Prediction.csv` – Dataset used for analysis and model development.
- `README.md` – Project documentation.

## How to Run

### Google Colab

1. Open `Mobile_Price_Prediction.ipynb` in Google Colab.
2. Upload `Mobile_Price_Range_Prediction.csv` to the Colab environment.
3. Run the notebook cells sequentially.

### Jupyter Notebook

1. Download or clone this repository.
2. Keep the following files in the same directory:

`Mobile_Price_Prediction.ipynb`
`Mobile_Price_Range_Prediction.csv`

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
