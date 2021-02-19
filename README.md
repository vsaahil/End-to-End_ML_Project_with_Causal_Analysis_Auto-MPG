# End-to-End_ML_Project_with_Causal_Analysis_Auto-MPG

## About the Dataset
This project showcases an End-to-End ML Project on the Auto MPG dataset, sourced from the UCI Machine Learning Repository. 
Link: http://archive.ics.uci.edu/ml/datasets/Auto+MPG

The dataset contains 398 instances and 8 attributes related to the city-cycle fuel consumption of various cars from the 1970s and 80s.


## Data Dictionary:
1. MPG (Continuous): Miles per Gallon  - a metric of vehicle's fuel effiency
2. Cylinders (Multi-Valued Discrete): Number of Engine Cylinders
3. Displacement (Continuous): The engine displacement - measured in cubic inches (although 'cc' or 'cubic cm' is a more common unit, this dataset has the values in 'cubic inches')
4. Horsepower (Continuous): The brake horsepower of the car's engine - measured in bhp
5. Weight (Continuous): Weight of the car (in lbs)
6. Acceleration (Continuous): Time taken for the vehicle to accelerate from 0 to 60 mph, in seconds
7. Model Year (Multi-Valued Discrete): The car model's year of manufacturing (denoted by the last 2 digits of the year e.g. 1976 -> '76')
8. Origin (Multi-Valued Discrete): The country of Origin/Model Production (1: Canada, 2: USA, 3: Britain)


## Objective: 
The main objective of the project is to predict miles per gallon (MPG) of a car, based on its given attributes. This prediction would greatly help the designer engineers to understand what would be the expected MPG of their designed car and help them make suitable changes to deliver a better product. 
This analysis would result in a number of important features which would be correlated to the target variable i.e. MPG
Since, "Correlation does not always imply causation", a Causal Analysis would be done to determine which features have significant positive/negative causation on MPG value

## Data Science Lifecycle Steps:
1. Framing the Problem
2. Data Acquisition
3. Data Exploration:
<br>• Data type of columns
  • Null values
  • Outliers
  • Distribution in attributes - continous and categorical
  • Correlation Plot
4. Data Preparation
5. Modelling
  • Training Models and Selection - Linear Regression and Random Forest
6. Model Fine-Tuning
7. Feature Importance Check
8. Model - Results and Conclusion
9. Causal Inference (using DoWhy)
  • Treatment Variables
  • Target Variable
10. Final Results and Causal Inference
  
