**🚀 Spaceship Titanic Survival Prediction**

This project is part of a Kaggle competition aimed at predicting passenger survival aboard the interstellar Spaceship Titanic. By analyzing unique space travel data, the goal is to build robust machine learning models to classify whether a passenger survived or not during the voyage.

**📌 Project Overview**

The Spaceship Titanic dataset simulates a futuristic space travel scenario with passengers divided into cabins, traveling to different destinations. The competition requires participants to predict survival outcomes based on provided features.

**🛠 Technologies Used**

Programming Language: Python
Libraries:
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost 

**📂 Dataset**
Source: Kaggle:- https://www.kaggle.com/competitions/spaceship-titanic

Key Features:

PassengerId: Unique ID for each passenger.
HomePlanet: Planet the passenger departed from.
CryoSleep: Whether the passenger elected to be in cryosleep.
Cabin: Passenger’s cabin number.
Destination: Destination of the passenger.
Age: Age of the passenger.
VIP: Whether the passenger paid for special VIP services.
Various spending features (e.g., RoomService, FoodCourt, ShoppingMall, etc.).
Target Variable:

Transported: Whether the passenger was transported to an alternate dimension (1 for yes, 0 for no).

**📈 Project Workflow**

Data Loading & Exploration:

Load the training and testing datasets.
Perform exploratory data analysis (EDA) to uncover trends and patterns.
Data Preprocessing:

Handle missing values.
Encode categorical features.
Scale numerical features.
Engineer new features for better model performance.
Model Building:

Train classification models like Logistic Regression, Random Forest, or Gradient Boosting.
Use cross-validation to ensure robustness.
Apply hyperparameter tuning for optimal performance.
Evaluation:

Assess model performance using metrics like accuracy, precision, recall, and F1-score.
Visualize results and feature importance.
Submission:

Generate predictions for the test dataset and create the submission file in Kaggle's required format.

**📊 Results**

Achieved 75% accuracy on the test set.
The model effectively identified important features like HomePlanet, CryoSleep, and Cabin.
