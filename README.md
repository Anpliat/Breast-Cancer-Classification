# Breast-Cancer-Classification

### Scope
Breast cancer is a type of cancer that occurs when some cells in the breast grow excessively. This type of cancer causes the greatest number of cancer-related deaths among women. There are different types of breast cancer based on the occurrence of the tumor. A tumor is a cluster of abnormal cells. 

The current project aims to classify cancer tumors as either malignant (spreading) or benign (non-spreading) using machine learning models with the help of breast cancer data.

### Dataset Description
The dataset was composed of 569 observations, 30 input variables and one target variable. Out of the 569 cancer tumors, 357 (63%) were labeled as benign tumors and 212 (37%) as malignant tumors.

### Contents
This repository contains the following files:
Filename | Content
--- | ---
Assessment.ipynb | This notebook contains the methodology for classifying breast cancer tumors using supervised learning techniques
Neural_Networks.ipynb | This notebook contains the methodology for classifying breast cancer tumors using a Neural Network architecture
pickle_model.pkl | This file contains the winning model trained and ready to be used
requirements.txt | This file contains all the project dependencies (libraries) needed for the current project to run

Below, we give an overview of the contents of the two notebooks:

:arrow_right: Assessment.ipynb

🠊 **Dataset & Dependencies**
* Import packages & data
* Dataset dimensions
* Data types per attribute


🠊 **Exploratory Analysis**
•	Statistical summary per attribute
•	Class Distribution
•	Univariate Analysis (Bar plots & density plots)
•	Multivariate Analysis (Correlation analysis)
•	Extra Visualizations (Mean radius & mean texture)

🠊 **Data Preparation**
•	Check the existence of missing values
•	Check the existence of duplicate rows
•	Removal of highly correlated features

🠊 **Feature Engineering**

🠊 **Methodology**
•	Data Splitting
•	Algorithm Selection
•	Feature Scaling
•	Model Building
•	Model Evaluation


🠊 **Model Finalization**
•	Select the winning algorithm
•	Evaluation of the winning algorithm on the validation set
•	Train the winning algorithm over the entire dataset
•	Archive the winning model for future use

🠊 **Discussion**


:arrow_right: Neural_Networks.ipynb
•	Import packages & data
•	Removal of highly correlated features
•	Data Splitting
•	Build and evaluate an Artificial Neural Network (ANN) model
