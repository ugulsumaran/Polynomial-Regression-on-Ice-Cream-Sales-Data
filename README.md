# Ice Cream Sales Prediction with Polynomial Regression 🍦 

This project demonstrates how Polynomial Regression can be used to model a non-linear relationship between temperature (°C) and ice cream sales.
Using Python and Scikit-learn, the notebook explores how polynomial features help capture the curvature in data where linear regression fails to fit accurately.


## Project Overview

### Dataset
The dataset `icecream.csv` contains 49 observations with two numerical variables:

- **Temperature (°C):** The ambient temperature in degrees Celsius.  
- **Ice Cream Sales (units):** The number of ice creams sold at the corresponding temperature.

The data illustrates a non-linear relationship — as temperature increases, ice cream sales rise, showing that polynomial regression can better capture this pattern compared to a simple linear model.

- Dataset Link: https://www.kaggle.com/datasets/mirajdeepbhandari/polynomial-regression/data


### The notebook performs the following key steps:
1. Data Loading & Exploration
- Loads the dataset icecream.csv
- Displays shape, types, and sample rows
- Checks for missing values
- Generates descriptive statistics
2. Exploratory Data Analysis (EDA)
- Visualizes temperature distribution using boxplots
- Displays correlation heatmaps to identify relationships
- Shows variable distributions via histograms
- Plots scatter/joint plots to visualize the link between temperature and sales

3. Model Implementation
- Builds a Linear Regression baseline model
- Creates a Polynomial Regression model fitted for degrees 1 to 5 using PolynomialFeatures and LinearRegression
- Uses a pipeline for cleaner model building

4. Model Evaluation
- Evaluates models using R² score, Mean Squared Error (MSE), Root Mean Square Error (RMSE)
- Compares model performance and visualizes fitted curves

## Libraries Used
- pandas, numpy — data handling
- matplotlib, seaborn — visualization
- scikit-learn — polynomial features, regression, evaluation

## How to Run

1. Clone the repository:
 ```bash
git clone https://github.com/yourusername/icecream-polynomial-regression.git
```

2. Navigate to the directory:
 ```bash
cd icecream-polynomial-regression
```

3. Open the Jupyter Notebook:
 ```bash
jupyter notebook icecream_PolynomialReg.ipynb
```

4. Ensure icecream.csv is in the same directory.

5. Run the cells step-by-step. Key functions:
- check_df(): Data overview.
- fit_polynomial_regression(): Fits models.
- evaluate_models(): Computes metrics.
- plot_linear_vs_polynomial(): Visualizes fits (main plot in the notebook).
- run_polynomial_analysis(): Runs everything (commented out by default).





## Results
- The polynomial regression model (degree 2 or 3) fits the data significantly better than linear regression.  
- R² score improves notably, and the fitted curve captures the rise in sales at higher temperatures.  
- Visualization clearly shows how polynomial regression follows the data’s curvature.


## 👩‍💻 Author
Developed by **Ümmügülsüm Aran**  
For questions or feedback, feel free to connect on [LinkedIn](https://www.linkedin.com/in/ummugulsumaran) ✨

## LICENSE 
Copyright (c) 2025 Ümmügülsüm Aran
MIT License - See [LICENSE](LICENSE) file for details




