# Used Car Price Prediction Project - Rusty Bargain

## Project Description

Rusty Bargain, a used car sales service developing an app to attract new customers, needs a model to determine the market value of cars. This app allows users to quickly find out the market value of their car using historical data, technical specifications, trim versions, and prices. The goal of this project is to create a model that accurately predicts the market value of used cars.

Rusty Bargain is interested in:

* Prediction quality
* Prediction speed
* Training time

## Project Instructions

1.  **Data Exploration:**
    * Download and examine the provided dataset.
2.  **Model Training:**
    * Train different models with various hyperparameters.
    * Implement at least two different models (gradient boosting, random forest, decision tree, linear regression).
    * Compare gradient boosting methods with random forest, decision tree, and linear regression.
3.  **Analysis:**
    * Analyze the speed and quality of the models.
4.  **Evaluation:**
    * Use the RMSE metric to evaluate the models.

## Data Description

The dataset is stored in `car_data.csv`.

### Features

* `DateCrawled`: Date profile was downloaded from the database
* `VehicleType`: Vehicle body type
* `RegistrationYear`: Vehicle registration year
* `Gearbox`: Gearbox type
* `Power`: Power (hp)
* `Model`: Vehicle model
* `Mileage`: Mileage (km)
* `RegistrationMonth`: Vehicle registration month
* `FuelType`: Fuel type
* `Brand`: Vehicle brand
* `NotRepaired`: Vehicle repaired or not
* `DateCreated`: Profile creation date
* `NumberOfPictures`: Number of vehicle pictures
* `PostalCode`: Owner's postal code
* `LastSeen`: Date of last user activity

### Target

* `Price`: Price (Euros)

## Project Structure
