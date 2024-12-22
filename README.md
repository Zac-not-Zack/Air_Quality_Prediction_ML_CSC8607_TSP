# 🤖 Projet ML : Prediction of the quality of air 📇
Pollutants in focus : CO (target), NMHC, C6H6, NOx, NO2, O3

Other variables : Humidity, Temperature

Contributor : WONG Hoe Ziet (TSP MAIA 2025 🐝)

# 🔡 Dataset
The dataset contains the data recolted from gas sensors deployed in an Italian city. Sensor reponses were gathered on the hourly basis.
Available at : https://archive.ics.uci.edu/dataset/360/air+quality

# 🎯 Objective 
Develop a ML regression model that is capable of predicting the concentration of CO gas by using the concentration level of other gases, humidity level, temperature as well as time pattern.

# 💻 Machine Learning
The ML library used : Scikit-Learn

ML models used in this project : Linear Regression (LR), Decision Tree (DT), Random Forest (RF), RANSAC, Ridge, K-Nearest Neighbors (KNN) and Dummy Regressor (DR)

Choosen metrics : MAE & R2 score

The results of different models and visualizations of data are directly available in the notebook.

# 📓 Content of the notebook
This notebook contains notably the code of the project and also the results of execution of different sections of the project.

The notebook is consisted of :

  1. Libraries & Dataset Loading 
  2. Dataset Exploration, Analysis & Cleaning
  3. Preprocessing & Initial Fittings with 3 models (LR, RF & DT)
  4. Hyperparameters Tuning and Regularization of Features
  5. Exploration of RANSAC model
  6. Ablations Studies
  7. Error Analysis
  8. Comparison of RF to baseline models (DR & KNN)
   

# :lady_beetle: Reporting Bugs

Teamwork is the key, please report at (https://github.com/Zac-not-Zack/Air_Quality_Prediction_ML_CSC8607_TSP/issues) if you come across any bug.


# :warning: Licence

[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/DAVFoundation/captain-n3m0/blob/master/LICENSE)

MIT License

Copyright (c) 2024 Wong Hoe Ziet 


