# Easy-SVM

Welcome to Easy-SVM! This project offers a clear, step-by-step guide for training a Support Vector Machine (SVM) to predict the severity of traffic accidents.

Our aim is to provide an accessible step-by-step tutorial for training a model using real-world data. You'll learn about the necessity of Exploratory Data Analysis, as well as cleaning and standardizing data for subsequent use. Additionally, you'll discover how to apply techniques like SMOTE to address issues such as class imbalances.


## Objective
---------
Predict whether a fatal/serious casualty occurs using road traffic data about the casualty, accident, and vehicles involved.

## Data
----
> Casualty (primary)
	Description: Data on the person(s) involved in the casualty
	Found as casualty_train.csv
> Vehicle (secondary)
	Description: Data on the vehicles involved in the casualty
	Found as vehicle_train.csv
> Data Dictionary (reference)
	Description: Field descriptions and value mappings
	Found as Reference

## Target
------
Whether `casualty_severity` in the casualty dataset is fatal (1) or serious (2), where (3) is slight. 
#### Note: will need to map target to binary 1 (fatal, serious) and 0 (slight).

## Quickstart

1. **Data Preparation**: Clone the repository and navigate to the `data` directory to find the pre-processed datasets ready for training.
2. **Environment Setup**: Install the required dependencies using `pip install -r requirements.txt`.
3. **Training, Evaluation and Prediction**: Navigate to the `Lab.ipynb` notebook. The notebook is annotated, mentioning each step that was taken during the process. Either run each cell individually or run them all. 