# Uber Pickups in New York City: Data Analysis and Demand Prediction

## 1. Overview

This project analyzes Uber pickup data in New York City from January to June 2015.  The goal is to understand the dynamics of Uber demand, identify factors influencing demand, and build a predictive model.

## 2. Goals and Objectives

*   **Main Goal:** Understand how Uber demand changes over time (hourly, daily, weekly, seasonally) and predict this demand.
*   **Objectives:**
    *   Load and clean the Uber pickup data.
    *   Explore temporal patterns of demand (hourly, daily, weekly, seasonal).
    *   Analyze the spatial distribution of demand (by NYC boroughs/areas).
    *   Identify factors influencing demand (weather, holidays, events, etc. - *to be added later as we analyze*).
    *   Build a model to predict the number of pickups for a given time period.
    *   Evaluate the model's performance and suggest improvements.

## 3. Data Source

*   **Source:** Data is from Kaggle: [Uber Pickups in New York City](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city).
*   **Description:** The dataset contains information on over 14 million Uber pickups in New York City between January and June 2015.
* **License:** CC0: Public Domain. (Checked on Kaggle)

## 4. Data Dictionary

| Column Name     | Description                                      | Data Type | Example                 |
| :-------------- | :----------------------------------------------- | :-------- | :---------------------- |
| `Date/Time`    | Date and time of the pickup                     | datetime64[ns]  | 2015-01-01 00:00:00     |
| `Lat`           | Latitude of the pickup location                | float64   | 40.721319              |
| `Lon`           | Longitude of the pickup location               | float64   | -73.997135             |
| `Base`           | TLC (Taxi and Limousine Commission) base code for Uber | object    | B02512                |

## 5. Tools and Libraries

*   Python 3.x
*   Jupyter Notebook: Development environment.
*   Pandas: Data manipulation and analysis library.
*   NumPy: Numerical computing library.
*   Scikit-learn: Machine learning library.
*   Matplotlib: Data visualization library.
*   Seaborn: Data visualization library (built on Matplotlib).
*   SQL (PostgreSQL): Database

## 6. Project Structure

*   `.gitignore`: File specifying intentionally untracked files that Git should ignore.
*   `README.md`: This file (project description).
*   `.venv/`: (Virtual environment directory - *not in the repository, only locally*).
*   `data/`: Directory for storing data.
    *   `uber-raw-data-janjune-15.csv`: Raw data file.
*   `notebooks/`:
    *   `01_data_loading_and_eda.ipynb`: Jupyter Notebook with data loading and initial exploratory data analysis.
*   `src/`: (Directory for helper scripts - *if needed*)

## 7. Results

*(To be filled in as the project progresses. Summary of key findings.)*

## 8. Usage
*(Will add as the project evolves and features appear.)*
Instructions on setting and starting.
