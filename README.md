# Project_Capstone-Building-regressive-models-to-predict-restauarant-ratings
### Objective: Analyze restaurant data to perform EDA, build predictive models, and derive actionable insights
- This project involves the following steps:
### 1. Data Exploration
#### a. Dataset Overview (Data Understanding):
- This steps explores dataset dimension, check for missing values and perform data conversion as needed.
#### b. Target variable:
- Analyse "Aggregate rating" distribution, and address any class inbalances
#### c. Descriptive Analysis:
- Involves calculating the statistics for the numerical columns, exploring categorical variables, and identifying top 5 cuisines and cities
### 2. Data Visualisation
#### a. Visualisation
- Creates Histograms to check for distributions, bar plots, and boxplots of ratings
- Compares average ratings across cuisines and cities
#### b. Geospatial Analysis
- Map restaurant locations using the coordinates
- Analyse distribrution across cities
- Correlate location with ratings
#### c. Additional Analysis
- Identify outliers and their effects
- Determine relationship between votes and ratings
### 3. Customer Preferences
- Analyse relationships between cuisines and ratings
- Identify popular cuisines by votes
- Determine which price ranges recieves highest rating
- Compare restaurant with and without table bookings
#### Additional Insights
#### a. Table booking impact
- Determine if table availability affects ratings across different cities
- Compare average ratings with and without this feature
#### b. Online delivery Analysis
- Calculate the percentage of the restaurants offering delivery
- Analyse availability across different price range
#### c. Customer Preferences
- Identify specific cuisin that consistently recieve higher ratings
- Determine city-specific preferences
### 4. Predictive Modeling
#### a. Feature engineering
- Extract additional features from existing columns
- Create features by encoding categorical columns
#### b. Modeling
- Build regressive models to predict restaurant ratings
- Split data into training and testing datasets
- Fit the models
#### c. Model Evaluation
- Evaluate models using RMSE, MAE, and R-squared
- Compare different algorithms like linear regression and random forest
