# Data-preprocessing-using-Water-Potability-dataset
Performing data preprocessing on the water potability dataset from Kaggle. The dataset was downloaded from https://www.kaggle.com/datasets/adityakadiwal/water-potability.
# About the Dataset
## Context
Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.

The water_potability.csv file contains water quality metrics for 3276 different water bodies. It has 10 columns, namely pH, Potability, hardness, solids, chloramines, sulfate, conductivity, organic_carbon, trihalomethanes and turbidity

#Objectives
To perform data preprocessing and prepare the dataset before machine learning algorithms can be done on it.

#Steps taken
* Getting the dataset
* Importing the libraries
* Importing the dataset
* Clean the dataset (Fill the missing values, if present)
* Encode categorical data, if any. For this case, there was no categorical variable(s) to be encoded.
* Split the dataset into training and testing sets in the ratio 70:30
* Perform feature scaling to ensure no variable dominates over the other just because of its measurements
