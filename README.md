# California Housing Price Predictor 🏠

**Linear Regression Model** - Artificial Intelligence & Machine Learning Task 1

## Objective
Build and evaluate a Linear Regression model to predict median house prices in California using the California Housing Dataset.

## Dataset
- **Source**: Built-in `sklearn.datasets.fetch_california_housing()`
- **Number of Samples**: 20,640
- **Number of Features**: 8
- **Target Variable**: `MedHouseVal` (Median House Value in $100,000s)

## Features
- `MedInc` — Median income in block group
- `HouseAge` — Median house age in block group
- `AveRooms` — Average number of rooms per household
- `AveBedrms` — Average number of bedrooms per household
- `Population` — Block group population
- `AveOccup` — Average number of household members
- `Latitude` — Block group latitude
- `Longitude` — Block group longitude

## Technologies Used
- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Model Performance
- **Mean Absolute Error (MAE)**: 0.5332
- **Root Mean Square Error (RMSE)**: 0.7456
- **R² Score**: 0.5758

## Key Insights from EDA
- Strong positive correlation between `MedInc` (Median Income) and house price.
- House location (Latitude & Longitude) also plays an important role.
- Linear Regression gives a reasonable baseline performance for this dataset.

## Project Files
- `California_Housing_Linear_Regression.ipynb` → Complete Jupyter Notebook (EDA + Model + Visualizations)
- `california_housing_model.pkl` → Trained Linear Regression model
- `Report.pdf` → Project Presentation Slides

## How to Run the Project
1. Open `California_Housing_Linear_Regression.ipynb` in Jupyter Notebook
2. Run all cells
3. The model will be trained and evaluated automatically

---
**Completed as per Task Requirements**  
Submitted for: Artificial Intelligence & Machine Learning - Task 1
