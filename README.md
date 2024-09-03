# House_Prediction-Model

# Overview
This repository presents a comprehensive approach to predicting house prices using various regression models. The dataset includes features such as PartRange, numPrevOwners, made, isNewBuilt, hasStormProtector, basement, attic, garage, hasStorageRoom, hasGuestRoom, price, and cityCode_encoded. The primary objective is to build, evaluate, and compare different regression models to accurately predict house prices based on these features.

# Dataset
The dataset encompasses the following features:
•	PartRange: The range of the city part.
•	numPrevOwners: Number of previous owners.
•	made: The year the house was built.
•	isNewBuilt: Indicates whether the house is newly built (1 for yes, 0 for no).
•	hasStormProtector: Indicates if the house is equipped with a storm protector.
•	basement: Indicates whether the house has a basement.
•	attic: Indicates whether the house has an attic.
•	garage: Number of garage spaces available.
•	hasStorageRoom: Indicates if the house includes a storage room.
•	hasGuestRoom: Indicates if the house includes a guest room.
•	price: The market price of the house (target variable).
•	cityCode_encoded: Encoded city code representing the location of the house.

# Code
This repository contains code for building and evaluating multiple regression models, including:
•	Linear Regression
•	Decision Tree Regression
•	Random Forest Regression
The code covers the entire pipeline from data preparation and feature engineering to model training, evaluation, and making price predictions for new instances.

# Key Components:
1.	Data Preparation: Handling missing values, encoding categorical features, and scaling.
2.	Feature Engineering: Constructing relevant features to enhance model performance.
3.	Model Training: Training various regression models on the dataset.
4.	Model Evaluation: Assessing model performance using metrics like Mean Squared Error (MSE) and R-squared (R²).
5.	Prediction: Making price predictions for new, unseen data.

# Insights
Initial analysis and model evaluations highlight differences in accuracy and performance among the models.
•	Linear Regression: Demonstrates a lower Mean Squared Error (MSE), suggesting a strong linear relationship between features and house prices. It offers a simpler, more interpretable model.

•	Decision Tree Regression: Captures more complex patterns but exhibits higher MSE, indicating potential overfitting on the dataset.

•	Random Forest Regression: Improves generalization by averaging multiple decision trees, reducing overfitting, but still shows higher MSE compared to Linear Regression, reflecting the complexity of the underlying patterns.

These insights guide the selection of the most appropriate model based on the trade-off between interpretability and predictive performance.

