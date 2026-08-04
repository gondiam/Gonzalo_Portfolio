# Gonzalo Díaz Amor
### Data Scientist & AI Engineer

Hi! I'm Gonzalo, a Data Scientist and AI Engineer with hands-on experience building end-to-end machine learning systems — from exploratory analysis and classical ML to deep learning and explainable AI. Below is a selection of my personal and academic projects.

📄 [CV](https://github.com/gondiam/cv/raw/main/output/CV_Gonzalo_DiazAmor_EN.pdf) · 💼 [LinkedIn](https://www.linkedin.com/in/gdiazamor/) · 🐙 [GitHub](https://github.com/gondiam) · ✉️ [Email](mailto:gdiazamor.ds@gmail.com)

## Featured Projects

# [Project 1: Churn Customers Prediction](https://github.com/gondiam/Churn_prediction)
* An Exploratory Data Analysis (EDA) was performed to understand the data and compare between groups of the population
* Comparing groups by graphs: density and boxplot for real variables, barplot otherwise
* Resampling and feature engineering were important due to the imbalanced dataset
* At the end an XGBoost model was used for classification, with GridSearch to tune hyperparameters and improve performance

![](/images/Customer_churn.jpeg)

# [Project 2: Breast Cancer Detection using Random Forest](https://github.com/gondiam/gondiam/blob/main/GDA_Explainable_AI_Graded_Hands_on_Exercise.ipynb)
(recommended to open in colab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Hrwu1jxexvL3jEfAgut6U_x_wJyu-jWC#scrollTo=FCDSTpWtb-nx&uniqifier=1)

Breast cancer is a type of cancer that starts in the breast. Cancer starts when cells begin to grow out of control. Breast cancer cells usually form a tumor that can often be seen on an x-ray or felt as a lump. Breast cancer occurs almost entirely in women, but men can get breast cancer, too. A benign tumor is a tumor that does not invade its surrounding tissue or spread around the body. A malignant tumor is a tumor that may invade its surrounding tissue or spread around the body.

In this project I develop a random forest solution with an emphasis on using SHAP (SHapley Additive exPlanations), a unified approach to explain the output of any machine learning model.
[SHAP explanation](https://shap.readthedocs.io/en/latest/index.html)

![](/images/XAI_BreastCancer.PNG)

# [Project 3: Exploratory Data Analysis: Personal Key Indicators of Heart Disease](https://github.com/gondiam/gondiam/blob/main/Heart_Disease.ipynb)
Take a look at the Kaggle URL where you can download the [data](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease).
According to the CDC, heart disease is one of the leading causes of death for people of most races in the US (African Americans, American Indians and Alaska Natives, and white people). About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Other key indicators include diabetic status, obesity (high BMI), not getting enough physical activity, or drinking too much alcohol. Detecting and preventing the factors that have the greatest impact on heart disease is very important in healthcare. Computational developments, in turn, allow the application of machine learning methods to detect "patterns" from the data that can predict a patient's condition.

![](/images/Personal-Key-Indicator-of-Heart-Disease.jpg)

# [Project 4: ICU Transfers 2019-2021](https://github.com/gondiam/visualization_timeseries)
* Using the highcharter library, I developed a time-series visualization of ICU transfers for a region of Spain
* Interactive comparison between periods across more than 20 hospital bases
* A summary of different parameters per base
* A boxplot to visualize the distribution of transfer records overall and per year
* Total number of transfers per year and base

![](/images/Transfers.PNG)

## Academic & Bootcamp Projects

# [Project 5: DPhi Bootcamp — Gender Determination by Morphometry of Eyes](https://github.com/gondiam/gondiam/blob/main/bootcampdphi_def_GDA.py)
Problem Statement

The anthropometric analysis of the human face is an essential study for performing craniofacial plastic and reconstructive surgeries.
Facial anthropometrics are affected by various factors such as age, gender, ethnicity, socioeconomic status, environment, and region.

The objective was to build a model to scan the image of a patient's eye and determine gender.

A deep learning model using TensorFlow and Keras achieved 92.4512% correctly labeled images in the competition, ranking 37th out of 91.

![](/images/bootcamp_DPhi.jpeg)

# [Project 6: Ethereum Price Forecasting with an LSTM Neural Network](https://github.com/gondiam/gondiam/blob/main/LSTM_loockback_1.ipynb)
Problem Statement

Cryptocurrency price volatility is one of the main challenges in financial time-series forecasting.

The objective was to explore how far a sequence model could go on this problem, using a Long Short-Term Memory (LSTM) network — a type of recurrent neural network suited to sequence dependence, capable of training successfully on very large architectures.

The model achieved a Root Mean Squared Error (RMSE) of 0.1 on the held-out test period. As with any short-horizon price forecast, this is best read as a modeling exercise rather than a trading-ready system.

![](/images/LSTM_loockback_1.PNG)

**Thank you for the visit :)**
