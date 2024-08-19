# California Housing Prices Prediction

## Table of Contents
- [Project Overview](#project-overview)
- [File Structure](#file-structure)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Key Metrics](#key-metrics)
- [Installation](#installation)

## Project Overview
The goal of this project is to predict housing prices in California based on features such as geographical location, number of rooms, and median income using the California Housing Prices dataset. This analysis involves data preprocessing, exploratory data analysis, model building, and evaluation.

## File Structure
The project directory contains the following files:

- `README.md`: This file.
- `housing.csv`: The raw dataset used for housing price prediction.
- `analysis.ipynb`: Jupyter Notebook for exploratory data analysis and model training.
- `analysis.html`: HTML version of the analysis notebook for easy viewing.
- `requirements.txt`: Python package dependencies.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Data Source
The dataset used in this project is the California Housing Prices dataset, which includes features related to housing characteristics and the median house value in California districts.[here](https://www.kaggle.com/datasets/camnugent/california-housing-prices/data).

## Methodology
1. **Data Preprocessing**: 
   - Handle missing values.
   - Encode categorical variables.
   - Normalize numerical features.
2. **Exploratory Data Analysis**:
   - Analyze feature distributions.
   - Examine relationships between features and the target variable.
3. **Model Building**:
   - Implement regression models to predict housing prices.
   - Evaluate model performance using metrics like RMSE and R² Score.
4. **Model Refinement**:
   - Tune hyperparameters to improve model accuracy.

## Key Metrics
- **Root Mean Squared Error (RMSE)**: Measures the average deviation between predicted and actual values.
- **R² Score**: Indicates the proportion of variance in the dependent variable that is predictable from the independent variables.

## Detail:
For a detailed explanation of the results and visualizations, please refer to the blog post available [here](https://tamokiloi.github.io/).

## Installation
To set up the project environment, install the required Python packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
