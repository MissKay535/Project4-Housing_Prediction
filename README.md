# Project4-Housing_Prediction

Housing Price Prediction Project

This project aimed to predict housing prices using machine learning models with the goal of achieving 90% accuracy. The data, sourced from Kaggle’s “Housing Prices Dataset” by M. Yasser H, consists of a mock dataset with 545 rows representing various housing features and prices.

**Data Source**

	•	Dataset: Housing Prices Dataset
	•	Source: Kaggle
	•	Features: Contains various attributes of houses to assist in predicting the price.

**Data Cleaning**

Initial data cleaning involved removing subjective columns that could introduce bias or noise, such as:

	•	Guest room
	•	Preferred area
	•	Furnishing status

These columns were deemed too subjective and not directly influential in predicting housing prices.

**Model Experiments**

Four machine learning models were tested on the cleaned dataset:

	1.	Linear Regression - Accuracy: 61.0%
	2.	Random Forest - Accuracy: 52.5%
	3.	Gradient Boosting - Accuracy: 43.7%
	4.	Neural Network - Accuracy: 61.9%

**Further Data Cleaning**

After the initial models performed below the target accuracy, additional columns were removed to simplify the dataset and potentially improve performance.

The models were retrained on the further refined dataset:

	1.	Linear Regression - Accuracy: 59.3%
	2.	Random Forest - Accuracy: 54.1%
	3.	Gradient Boosting - Accuracy: 41.8%
	4.	Neural Network - Accuracy: 59.8%

It was observed that reducing columns further did not improve the accuracy and, in fact, reduced the R² score.

**Model Comparison**

Across both datasets, Neural Networks and Linear Regression consistently performed the best, while Gradient Boosting showed the lowest performance indicating it might not be suitable for this specific prediction task.

**Limitations**

	•	The dataset was artificial and limited to 545 rows. A larger, real-world dataset might yield better results and allow for more accurate model training.

**Summary**

	•	Four models were evaluated, with the Neural Network achieving the highest performance.
	•	Removing additional columns did not improve accuracy.
	•	The models did not reach the target accuracy of 90% but were able to make predictions with minimal outliers.

**Conclusion**

The project highlights the impact of data quality and quantity on machine learning model performance. Despite the limited dataset, the Neural Network model showed potential. For improved predictions, a larger dataset or additional features may be necessary.