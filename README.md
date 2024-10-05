# Flight Price Prediction App

The **Flight Price Prediction App** uses historical flight data to predict flight prices based on various factors such as departure and arrival times, duration, airline, and more. The goal is to help users find the best time to book flights and save money.

### Try the App Live
You can try the live version of the app here: [Flight Price Prediction App](https://flightpricepredictionmax.streamlit.app/)

## Features

- Predict flight prices using machine learning models
- Input various flight details like airline, source, destination, and more
- View the predicted price based on past trends

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Installation](#installation)
- [License](#license)

## Project Overview

This app takes in several flight-related inputs from the user and predicts the flight price using a trained machine learning model. The goal of the project is to provide users with estimated prices to help them choose the best flight based on budget and time.

## Technologies Used

- Python
- -XGBoost
- Streamlit (for deploying the web app)
- Scikit-learn (for machine learning model development)
- Pandas and NumPy (for data manipulation)
- Matplotlib and Seaborn (for data visualization)

## Data

The dataset used for this project contains flight booking information such as:

- **Airline:** The airline operating the flight
- **Source:** Departure city
- **Destination:** Arrival city
- **Date of Journey:** The travel date
- **Duration:** Time taken by the flight
- **Total Stops:** Number of stops the flight makes
- **Additional Information:** Miscellaneous info such as meal services or flight class

### Dataset Source:
You can find the dataset used for training the model in the `train.csv` file within the repository.

## Installation

To run this app on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Deepak20y/Flight-Prediction-app.git
