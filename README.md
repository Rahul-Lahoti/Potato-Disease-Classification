# Potato Disease Classification

This project focuses on the development of a machine learning model for classifying potato diseases. The aim is to create a model that can accurately identify and classify different diseases affecting potato plants, enabling timely intervention and effective disease management.

1. Model Setup:

Download the dataset from Kaggle, specifically the folders related to potato diseases.
Run Jupyter Notebook in your browser.
Copy code
jupyter notebook
Open the potato-disease-training.ipynb notebook.
Update the path to the dataset in cell #2.
Execute each cell in the notebook to train the model.
Save the generated model with a version number in the models folder.


2. Model Training:

Extensive Exploratory Data Analysis (EDA): Perform a thorough analysis of the dataset to gain valuable insights and understand the characteristics of potato diseases.
Feature Selection: Utilize correlation analysis to uncover the interrelationships among variables, helping to select the most important features for the classification task.
Model Robustness: Employ advanced techniques like Variance Inflation Factor (VIF) to mitigate multicollinearity and enhance the robustness of the model.


3. Model Evaluation:

Split the dataset into training and testing sets.
Evaluate the trained model using various metrics such as accuracy, precision, recall, F1 score, and AUC-ROC score.
Compare the performance of different models, such as Random Forest, Support Vector Machine (SVM), and Logistic Regression, to determine the most effective approach for potato disease classification.


4. Deployment:

Once the model is trained and evaluated, it can be deployed as a part of a larger application or integrated into an existing system for real-time disease classification.
The deployment process involves setting up an API or web service that can accept input data and provide predictions using the trained model.


Note: The project also includes setup instructions for the backend and app development, but for the purpose of this CV, the focus is solely on the machine learning model development and evaluation.


