# Supervised Learning for Health Insurance Premium Estimation

This project focuses on the development and evaluation of supervised learning models, specifically regression, to accurately predict individual health insurance premiums. By leveraging both linear regression and artificial neural networks (ANNs), we investigate which approach best captures the complex relationships between personal characteristics, health factors, and associated insurance costs.

**Dataset**

The project utilizes the "insurance.csv" dataset, containing the following features:

age: Age of the individual
sex: Gender of the individual (binary: 0 for female, 1 for male)
bmi: Body mass index (BMI)
children: Number of children covered by health insurance
smoker: Smoking status (binary: 0 for non-smoker, 1 for smoker)
region: The beneficiary's residential area in the US, encoded into binary variables for northwest, southeast, and southwest (northeast is the baseline)
charges: Individual medical costs billed by health insurance (the target variable)

**Project Structure**

Regression_Modeling_Insurance_Premiums.ipynb: The Jupyter Notebook containing the comprehensive code for data exploration, preprocessing, model implementation, evaluation, and premium prediction.
insurance.csv: The dataset used for the project.
README.md: This file.

**Technologies Used**

Python: The primary programming language for data manipulation and model development.
Pandas: For efficient data loading, cleaning, and analysis.
NumPy: For numerical operations and array manipulation.
Scikit-learn: For implementing and evaluating linear regression.
TensorFlow/Keras: For building, training, and evaluating artificial neural networks.
Matplotlib/Seaborn: For creating informative visualizations to explore data patterns and model performance.
