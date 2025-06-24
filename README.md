### AAI510 - Final Project - Flight Delay Model
Zach Artman, Jack Baxter, Greg Moore

### Note about the dataset
Delays are recorded as minutes from departure time

`negative` means departed early

`0` means on time

`positive` means departed late

Project Overview

This project, developed for the AAI-510-03 Machine Learning: Fundamentals and Applications course at the University of San Diego (Summer 2025), aims to predict flight delays using machine learning to optimize airline operational costs. Flight delays incur significant expenses, including $1,500–$3,000 in fuel costs per 30 minutes of delay and 10–15% additional crew wages, with daily wage costs at large airports ranging from $500–$2,000 per airline (Airlines for America A4A 2023 report). By leveraging historical flight data, this project enables airlines to predict delays based on patterns by airline and airport, facilitating proactive management, rerouting, or cancellation of flights to save thousands of dollars daily and enhance traveler satisfaction.

Authors: Greg Moore, Zachary Artman, Jack Baxter
Instructor: David Friesen
Submission Date: June 23, 2025
Course: AAI-510-03, University of San Diego
GitHub Repository: AAI510-FP-GRP1

Objectives

Develop machine learning models to predict length of flight delays using the Airline Delay Dataset.

Identify patterns in delays by airline, airport, and other features to provide actionable insights.

Enable airlines to optimize flight scheduling, reduce fuel and crew costs, and improve customer satisfaction.

Evaluate multiple models (e.g., Logistic Regression, Random Forest, XGBoost) and deploy the best-performing model (XGBoost multiclass classifier) for real-time predictions.

Dataset

Name: Airline Delay Dataset
Source: Kaggle
Size: ~5.8 million instances, 31 variables
Key Variables:

Temporal: YEAR, MONTH, DAY, DAY_OF_WEEK, SCHEDULED_DEPARTURE, SCHEDULED_ARRIVAL

Flight Info: AIRLINE, FLIGHT_NUMBER, TAIL_NUMBER, ORIGIN_AIRPORT, DESTINATION_AIRPORT

Delay Metrics: DEPARTURE_DELAY, ARRIVAL_DELAY, CANCELLED, DIVERTED

Other: DISTANCE, TAXI_OUT, TAXI_IN, AIR_TIME, delay reasons (e.g., WEATHER_DELAY)
The dataset provides comprehensive flight data for 2015, enabling robust exploratory data analysis (EDA) and model training.

Technologies Used
Programming: Python 3.9+
Libraries:
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn, xgboost
Dataset Access: kagglehub
Environment: Jupyter Notebook

Acknowledgments
University of San Diego, AAI-510-03 course
Instructor David Friesen for guidance
Kaggle for providing the Airline Delay Dataset
