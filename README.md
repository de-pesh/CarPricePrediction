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
   git clone https://github.com/de-pesh/car-price-prediction.git
   cd car-price-prediction

2. **Install Prerequisites mentioned above**
3. **Place the dataset:**
- Place the CarPrice.csv dataset into the root directory of the project.
4.	**Run the Jupyter Notebook:**
- Open the carPrice.ipynb file in a Jupyter Notebook and run the cells sequentially. The notebook will perform data exploration, feature selection, and model training.


## Dataset Description

The dataset CarPrice.csv contains the following features:

- car_ID: Unique identifier for each car.
-	CarName: Name and brand of the car.
-	fueltype: Type of fuel (gas or diesel).
-	aspiration: Type of engine aspiration (turbocharged or standard).
-	doornumber: Number of doors (two or four).
-	carbody: Car body type (sedan, hatchback, etc.).
-	drivewheel: Drive wheel type (FWD, RWD, etc.).
-	enginelocation: Location of the engine (front or rear).
-	enginesize: Size of the car’s engine.
-	horsepower: Power output of the engine.
-	citympg and highwaympg: Fuel efficiency in the city and highway.
-	price: The target variable representing the price of the car.

