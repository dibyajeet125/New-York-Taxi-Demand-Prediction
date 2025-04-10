# New-York-Taxi-Demand-Prediction
Developed a predictive model for NYC taxi demand using 12.7 million trip records, dividing the city into 40 clusters and analyzing demand across 4,464 10-minute intervals per month. This project achieved a test MAPE of approximately 11.7%.


This project involves developing a predictive model to forecast taxi demand in New York City. The goal is to accurately predict the number of taxi pickups at specific locations and times, enhancing taxi fleet management and passenger experience.

Key Features:

Dataset: Utilized over 12.7 million NYC Yellow Taxi trip records from January 2015 & January 2016.

Clustering: Divided NYC into 20 spatial clusters using MiniBatchKMeans to segment demand patterns.

Time-Binning: Analyzed demand in 4,464 10-minute intervals per month to capture temporal variations.

Feature Engineering: Incorporated historical demand, cluster coordinates, weekday indicators, and exponential weighted moving averages (EWMA) as predictive features.

Modeling: Implemented baseline models (SMA, WMA, EWMA) and advanced models (Random Forest, XgBoost) to evaluate performance.

Evaluation Metrics: Calculated Mean Absolute Percentage Error (MAPE) for model comparison.

Achievements:

Achieved a test MAPE of approximately 11.7% with advanced models.

Demonstrated the importance of feature engineering and hyperparameter tuning in improving model accuracy.

Code Structure:

Data Preprocessing: Scripts for outlier removal, clustering, and time-binning.

Model Implementation: Baseline and advanced model implementations with hyperparameter tuning.

Evaluation: Scripts for calculating MAPE and comparing model performances.

This project showcases a comprehensive approach to predicting taxi demand, providing insights into urban mobility optimization and fleet management strategies.

DATASET LINK: https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data
