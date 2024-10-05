# Income-Prediction-using-Machine-Learning
💰 Income Prediction Project 💰

📊 Project Overview
This project focuses on predicting whether a person's income exceeds $50K or falls below that threshold based on various demographic and employment-related factors. We utilize the Adult Census Income dataset from Kaggle, analyzing individual data such as age, education, occupation, and more.

🏷️ Problem Type
This is a supervised classification problem, aiming to predict a binary outcome: whether an individual’s income is above or below $50K.

📈 Dataset
The Adult Census Income dataset consists of approximately 32,561 rows and 15 features. Below are the key features:

Column Name	Description	Type
👤 age	The age of the individual.	int64
💼 workclass	Type of employment (e.g., Private, Self-Employed).	object
📊 fnlwgt	Final weight used to adjust for sampling in census data.	int64
🎓 education	Highest level of education attained (e.g., Bachelors, Masters).	object
🔢 education.num	Numerical representation of education level (0-16).	int64
💍 marital.status	Marital status of the individual (e.g., Married, Single).	object
👔 occupation	The individual’s occupation (e.g., Teacher, Engineer).	object
💑 relationship	Relationship status (e.g., Husband, Wife, Unmarried).	object
🌍 race	Race of the individual (e.g., White, Black, Asian).	object
👨‍👧 sex	Gender of the individual (e.g., Male, Female).	object
💰 capital.gain	Amount of capital gain in USD (integer).	int64
📉 capital.loss	Amount of capital loss in USD (integer).	int64
⏰ hours.per.week	Number of hours worked per week (integer).	int64
🌏 native.country	Country of origin of the individual (e.g., USA, Canada).	object
💵 income	Target variable indicating if income is >50K or <=50K.	object
🔗 Download the dataset from Kaggle.

🎯 Project Goals
The main objectives of this project are:

Data Preprocessing:

Cleaning the dataset and handling missing values.
Encoding categorical variables and scaling numerical features.
Exploratory Data Analysis (EDA):

Analyzing data distribution and relationships between features.
Visualizing key patterns for deeper insights.
Modeling:

Building various machine learning models including:
Logistic Regression 🤖
K-Nearest Neighbors (KNN) Classifier 🌐
Support Vector Classifier (SVC) 🚀
Decision Tree Classifier 🌳
Random Forest Classifier 🌲
Evaluation:

Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
🏆 Model Performance
After extensive testing and hyperparameter tuning, the Random Forest Classifier achieved:

Accuracy: 92.77% 📈
F1 Score: 93.08% 💯
These metrics showcase the model's effectiveness in predicting income levels based on the provided features.


