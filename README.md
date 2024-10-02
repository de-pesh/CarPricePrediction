# Car Price Prediction

This project aims to predict car prices based on various features of the vehicle using machine learning techniques. It involves data exploration, feature selection, and building a regression model.

## Project Structure

- **Imports**: The project begins by importing essential libraries for data manipulation, visualization, and modeling:
  - `pandas` for data handling.
  - `matplotlib` and `seaborn` for data visualization.
  - `sklearn` for machine learning tasks, including model training and evaluation.
  - `statsmodels` for statistical analysis and regression modeling.

- **Data Loading**: 
  - The dataset (`CarPrice.csv`) is loaded using `pandas.read_csv()`. This dataset contains various attributes of cars that will be used to predict their prices.

- **Data Exploration**:
  - Basic exploratory data analysis (EDA) is conducted to understand the structure of the data. This may include checking for missing values, summary statistics, and data distributions using visualization libraries like `seaborn` and `matplotlib`.

- **Feature Selection**: 
  - Recursive Feature Elimination (RFE) is used to select the most relevant features for the prediction model.

- **Modeling**:
  - A linear regression model is built using `sklearn` and evaluated using various performance metrics.
  - `statsmodels` is used to analyze the statistical significance of features and handle multicollinearity using Variance Inflation Factor (VIF).

## Getting Started

### Prerequisites
You need the following libraries installed to run this project:

```bash
  pip install pandas matplotlib seaborn scikit-learn statsmodels
```


## Running the Project

Follow these steps to run the project:

1. **Clone the repository**: First, clone the project repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
```
