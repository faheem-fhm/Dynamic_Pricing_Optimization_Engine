# Flight Price Prediction using Random Forest Regression

A machine learning project that predicts airline ticket prices using
**Random Forest Regression**. This project demonstrates data
preprocessing, feature engineering, model training, evaluation, and
prediction.

## Project Overview

Flight ticket prices vary depending on factors such as airline, source,
destination, travel class, number of stops, duration, departure time,
and booking date. This project builds a Random Forest Regression model
to predict ticket prices from historical flight data.

## Objectives

-   Predict flight ticket prices accurately.
-   Clean and preprocess the dataset.
-   Train a Random Forest Regression model.
-   Evaluate performance using MAE, MSE, RMSE, and R² Score.
-   Predict prices for new flight records.

## Dataset

**Features** - Airline - Source City - Destination City - Departure
Time - Arrival Time - Number of Stops - Travel Class - Flight Duration -
Days Left Before Journey

**Target** - Price

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Scikit-learn
-   Matplotlib
-   Jupyter Notebook

## Workflow

1.  Load and explore the dataset.
2.  Preprocess the data.
3.  Encode categorical variables.
4.  Split into training and testing sets.
5.  Train the Random Forest model.
6.  Evaluate model performance.
7.  Predict flight prices.

## Project Structure

    Flight-Price-Prediction/
    │
    ├── flight_price_with_using_random_forest.ipynb
    ├── dataset.csv
    ├── README.md
    └── requirements.txt

## Installation

``` bash
git clone https://github.com/your-username/Flight-Price-Prediction.git
cd Flight-Price-Prediction
pip install -r requirements.txt
```

## Run the Project

``` bash
jupyter notebook
```

Open `flight_price_with_using_random_forest.ipynb` and run all cells.

## Results

The Random Forest model learns the relationship between flight features
and ticket prices, providing reliable predictions for unseen data.

## Future Improvements

-   Hyperparameter tuning
-   Compare with XGBoost and LightGBM
-   Deploy using Flask or FastAPI
-   Integrate real-time flight data

## Author

**Mohamed Faheem**

If you found this project useful, consider giving it a ⭐ on GitHub.
