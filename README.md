# Room-Occupancy-Count-Prediction
This project aims to predict room occupancy counts using sensor data. It explores four different classification algorithms: Random Forest, Support Vector Machine, Gradient Boosting, and XGBoost, both with and without grid search. The project also includes comprehensive exploratory data analysis (EDA) and thorough data preprocessing.

_**Problem Statement**_

The goal of this project is to predict the number of occupants in a room based on sensor data. This information can be critical for optimizing energy consumption and improving resource management in buildings.

_**Dataset**_

The Project’s dataset contained 10130 records each record at different time and 18 features where each one represents a sensor reading such as CO2 and temperature.

_**Project Workflow**_
1.	Exploratory Data Analysis (EDA): Exploring the dataset, the relationship between the features and the target, and more.

2.	Data Preprocessing: Which involves cleaning the data and preparing it for the modeling stage such as scaling the data and dropping unnecessary columns. 

3.	Modelling stage: Implementing 4 classification algorithms, RF, SVM, Gradient boosting, XG boost, where each one was implemented with or without grid search to evaluate performance. 

_**Tech Stack**_
- Python: The main programming language used
- Pandas: For data manipulation
- Numpy: For numerical operations
- Scikit-learn: For model building and evaluation, and data preprocessing
- Matplotlib & Seaborn: For data visualization
- Google Colab: The main tool used for coding and experimentation

_**How to Use**_
1.	Room_Occupancy_Count_Prediction.ipynb Notebook:
   
-The notebook contains all steps from data preprocessing all the way to evaluating the results.

-To run each notebook, open the it in Google Colab:
  - Click on the notebook file (Room_Occupancy_Count_Prediction.ipynb).
  - Choose "Open in Colab" from the GitHub file preview.
  - You can run the cells sequentially to see the steps and results.

2.	Room Occupancy Prediction Report:
- The report (Room Occupancy Prediction Report.docx) includes: 
  1. A comprehensive review of all EDA and data preprocessing steps applied.
  2. A comparison between models and evaluation for the performance of each.
- You can view or download the report directly from the repository to understand the project background and conclusions.
