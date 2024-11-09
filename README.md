# Estimating Demand Curve of a Vegetable using OLS Regression
Economics Assignment on Demand Estimation by Prof. Kaushik Mandal.

- The final assignment PDF is [here](https://github.com/sensoubhik11/eco-assignment/blob/master/demand-curve-ols.pdf)
- The notebook detailing step-by-step calculations is [here](https://github.com/sensoubhik11/eco-assignment/blob/master/demand-curve-ols.ipynb)
- The demand curve plot is saved as an image [here](https://github.com/sensoubhik11/eco-assignment/blob/master/demand_curve_tomato.png)

## Introduction
This project estimates the demand curve for tomatoes in Paschim Bardhaman from September 1, 2024, to October 30, 2024. The data has been collected from [Agmarknet](https://agmarknet.gov.in/). The estimation utilizes the Ordinary Least Squares (OLS) regression method, calculating the demand curve by treating the price as the independent variable and quantity as the dependent variable.

## Project Description
This assignment is organized into a few main steps:

- **Data Collection**: Using data from Agmarknet, filtered for tomato arrivals and prices in the Paschim Bardhaman district.
- **Data Processing**: Cleaning and transforming data to fit the requirements for regression, including converting units for consistency.
- **Demand Curve Estimation**: Calculating the linear demand curve equation using OLS, with the slope and intercept representing the relationship between price and quantity.
- **Visualization**: Plotting the demand curve to visualize the relationship, with the final plot saved as a high-resolution image.

## File Structure
```
├── agmarknet_price_arrival.html   # HTML file with the raw data for the assignment
├── demand-curve-ols.ipynb         # Notebook with detailed OLS calculations and analysis
├── demand-curve.ipynb             # Notebook with use of readymade package for OLS
├── demand_curve_tomato.png        # Final plot of the demand curve
├── demand-curve-ols.pdf           # PDF of the completed notebook
├── LICENSE                        # Licensing information
├── requirements.txt               # Dependencies required to run the project
└── README.md                      # Project README file
```

## Dataset
The dataset contains information on tomato arrivals and prices in Paschim Bardhaman, with key fields such as:

- **Arrivals (Tonnes)**: Quantity of tomatoes arriving in the market. Its assumed that all the tomatoes have been sold.
- **Modal Price (Rs./Quintal)**: Price representing the market's typical rate.
- **Reported Date**: The date each entry was recorded.

## Installation

To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sensoubhik11/eco-assignment.git
   cd eco-assignment
    ```

2. You can create a virtual environment and then install the required packages using the following command:

    ```bash
    python -m venv venv
    source venv/bin/activate   # for linux
    .\venv\Scripts\Activate    # for windows
    pip install -r requirements.txt
    ```
3. Then run jupyer-lab which you can access at localhost:8888
   ```bash
   jupyter-lab
   ```
## How to Use
###### Demand Curve Estimation:
- Open `demand-curve-ols.ipynb` in Jupyter Lab.
- Run the cells sequentially to perform the full analysis, from data cleaning to calculating the regression coefficients and plotting the demand curve.
- The demand curve equation obtained is included at the end of the notebook, and the resulting plot can be found in the file `demand_curve_tomato.png`.