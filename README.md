# Australian Rain Prediction Project

## Overview

This project aims to predict whether it will rain tomorrow in Australia using 10 years of weather data from various weather stations across the country. By analyzing 23 different features, we employ machine learning techniques to build a predictive model.

## Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Objective](#objective)

## Dataset

- **Source:** [Kaggle - Rain in Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
- **Records:** 145,460 observations
- **Description:** Daily weather observations from numerous Australian weather stations.

## Features

Some of the key features in the dataset include:

- **Date:** Date of observation
- **Location:** Name of the weather station
- **MinTemp:** Minimum temperature in degrees Celsius
- **MaxTemp:** Maximum temperature in degrees Celsius
- **Humidity9am:** Humidity percentage at 9 AM
- **Humidity3pm:** Humidity percentage at 3 PM
- **RainToday:** Boolean indicating if it rained today
- **RainTomorrow:** Boolean indicating if it rained the next day (target variable)

## Objective

Utilize the provided weather features to predict the `RainTomorrow` variable, indicating whether it will rain the following day. This involves:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model building using classification algorithms
- Model evaluation and validation
