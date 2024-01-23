This Multi Class Classification project aims to classify the activity type performed by individuals based on smartphone sensor data. Using the data collected from the accelerometers and gyroscopes of smartphones, we apply machine learning algorithms to predict activities such as standing, walking, and lying down.

## Dataset
The dataset for this project includes time-series sensor data recorded from smartphones carried by individuals performing different activities. The activities are pre-labeled, and the data is segmented into windows with corresponding activity labels.

## Features
The dataset features include time and frequency domain variables derived from the sensor signals. The preprocessing steps involve noise filtering, normalization, and feature extraction.

## Machine Learning Pipeline
The analysis pipeline includes the following steps:
- Data Preprocessing: Cleaning and normalizing data, handling missing values, and feature scaling.
- Feature Selection: Identifying the most relevant features for activity recognition.
- Model Selection: Training and comparing different machine learning models such as Random Forest, Decision Tree, Gradient Boosting, Logistic Regression, XGBClassifier, AdaBoost Classifier
- Hyperparameter Tuning: Optimizing models for better accuracy using techniques like grid search.
- Model Evaluation: Assessing the performance of models using metrics such as accuracy, precision, recall, and confusion matrices.

## Key Findings
- Discussion of which models performed the best and insights gained from the model evaluations.
- Observations from the feature importance analysis and how different activities affect sensor readings.

## How to Use
Instructions for setting up the environment, running the analysis, and replicating the results:
1. Clone the repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter Notebook to see the step-by-step analysis.

## Requirements
A list of libraries and versions used in the project can also be found in `requirements.txt`.
