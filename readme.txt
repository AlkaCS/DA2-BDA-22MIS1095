#UCI Heart Disease Dataset
DA2-BIG DATA ANALYTICS
Alka C S  22MIS1095

#About the Dataset
The Heart Disease UCI dataset provides medical data that helps in diagnosing heart disease in patients.
It includes various clinical and demographic attributes. The goal is to predict the presence of heart disease based on these features.

#Key Features:
age: Age of the patient in years.
sex: Gender of the patient (1 = male; 0 = female).
cp: Chest pain type (4 types).
trestbps: Resting blood pressure (in mm Hg).
chol: Serum cholesterol in mg/dl.
thalch: Maximum heart rate achieved.
oldpeak: ST depression induced by exercise relative to rest.
ca: Number of major vessels (0-3) colored by fluoroscopy.
thal: A blood disorder called thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect).

#Requirements
Python 3.x
NumPy
Pandas
Matplotlib
MiniSom

You can install the required packages using pip:
pip install numpy pandas matplotlib minisom

#Project Overview
This project leverages Self-Organizing Maps (SOM) to cluster and visualize the patterns related to heart disease diagnosis.
It focuses on specific medical attributes, helping us identify clusters and patient segments based on their clinical profiles.

#Steps Involved:
Data Loading: Load the Heart Disease UCI dataset.
Data Preprocessing: Select relevant features, apply encoding for categorical variables, and scale the features.
SOM Initialization: Set up the SOM with specified grid dimensions and hyperparameters.
Training: Train the SOM using the selected data.
Visualization: Generate visual representations of the SOM's distance map and plot the patient clusters.

#How to Run the Implementation
Download the dataset (Heart Disease UCI dataset) and place it in the same directory as the script, naming it heart_disease_uci.csv.
Run the script using the following command:
python heart_disease_som.py

#Hardware Requirements
Any machine capable of running Python 3.x.
Minimum of 4GB RAM recommended for smooth execution.

#Software Requirements
Python 3.x: The programming language used for the implementation.
Libraries:
NumPy: For handling numerical operations and arrays.
Pandas: For loading, manipulating, and analyzing the dataset.
Matplotlib: For creating plots and visualizations.
MiniSom: A lightweight library for implementing Self-Organizing Maps.

#Author
Alka C S
22MIS1095