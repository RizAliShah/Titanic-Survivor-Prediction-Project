*Titanic Survival Prediction*

This project is a comprehensive walkthrough of building and evaluating various machine learning models to predict passenger survival on the Titanic. The notebook covers everything from data loading and preprocessing to feature engineering, model training, and evaluation.

Key Features
	Data Loading and Preprocessing: The notebook starts by loading the Titanic dataset and performing essential preprocessing steps, including handling missing values and converting categorical features to numerical ones.
 	Exploratory Data Analysis (EDA): The notebook includes a basic EDA section to visualize the relationships between different features and survival rates.
	Feature Engineering: New features such as 'FamilySize', 'IsAlone', 'Title', 'AgeBin', and 'FareBin' are created to improve model performance.
 	Model Training and Evaluation: The notebook implements and evaluates a wide range of classification models, including:
		Logistic Regression
		Random Forest
		Tuned Random Forest
		Random Forest with Feature Engineering
		XGBoost
		LightGBM
		Neural Network
		TensorFlow Decision Forests (Gradient Boosted Trees)
	Hyperparameter Tuning: The notebook demonstrates how to perform hyperparameter tuning using GridSearchCV for the Random Forest model and also explores tuning for the Gradient Boosted Trees model.
	Ensemble Modeling: An ensemble model is created by averaging the predictions of four different models to improve predictive accuracy.
	Model Comparison: The notebook includes a comprehensive comparison of all the trained models, with a bar chart to visualize their performance.
	Submission File Generation: The notebook generates a submission.csv file in the required format for submission to the Titanic competition on Kaggle.

Models Implemented
The following machine learning models were implemented and evaluated in this notebook:
Logistic Regression
Random Forest
XGBoost
LightGBM
Neural Network (using TensorFlow/Keras)
TensorFlow Decision Forests (Gradient Boosted Trees)
Ensemble Model (averaging the predictions of four models)

Results
The best-performing model was a Gradient Boosted Trees model from the TensorFlow Decision Forests library with a subsample of 0.8, which achieved an accuracy of 91.1% on the validation set.
The feature importance analysis revealed that 'Title', 'Pclass', and 'PassengerId' were the most influential features for predicting survival.
The final submission file was generated using the best-performing model.
How to Use
Clone the repository to your local machine.
Open the Titanic_Survival_Prediction.ipynb notebook in a Jupyter environment.
Run the cells in the notebook sequentially to reproduce the results.
The final submission file will be saved as submission_final.csv.
