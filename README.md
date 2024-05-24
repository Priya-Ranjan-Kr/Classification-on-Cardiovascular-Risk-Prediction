# Cardiovascular Risk Prediction

The Framingham Heart Study dataset is used in this project to employ machine learning techniques for forecasting the risk of cardiovascular disease over the next ten years. By utilizing classification algorithms, the project identifies critical risk factors, aiding medical practitioners in recognizing high-risk patients and taking preventive actions.

## Introduction
Cardiovascular diseases (CVDs) remain a leading cause of mortality worldwide. Early prediction and prevention are crucial in reducing the burden of CVDs on healthcare systems and improving patient outcomes. The Framingham Heart Study, initiated in 1948, has been instrumental in understanding the epidemiology of CVDs. It provides comprehensive data on various risk factors associated with cardiovascular events.
Leveraging this valuable dataset, our project aims to develop a robust machine learning model that can predict an individual's 10-year risk of developing cardiovascular disease. By identifying key risk factors and accurately predicting potential cardiovascular events, healthcare providers can implement early interventions, ultimately reducing the incidence and impact of these diseases.
## Project Overview

The primary objective of this research is to develop a machine learning model that leverages demographic, clinical, and laboratory data to predict an individual's 10-year risk of cardiovascular disease.

This study utilizes the Framingham Heart Study dataset, a renowned resource for predicting cardiovascular risk. The dataset encompasses information on 3,390 patients who were monitored for cardiovascular events over ten years. It includes 17 variables, such as age, sex, blood pressure, cholesterol levels, smoking status, and diabetes status.

The project begins with data preparation, addressing missing values, encoding categorical variables, and scaling numerical variables. After preprocessing, the dataset is split into training and testing sets in a 70:30 ratio.

Various machine learning algorithms are applied to the training data, including logistic regression, KNN, XGBoost, SVC, random forest, and Naive Bayes Classifier. These algorithms are selected for their proven efficacy in predicting cardiovascular risk. The training data is used to train the models, and their performance is evaluated on the testing data.

## Evaluation Metrics

The study employs several evaluation metrics, including accuracy, precision, recall, and the area under the receiver operating characteristic curve (AUC-ROC). These metrics provide a comprehensive assessment of the machine learning models' performance.

## Results

The results indicate that XGBoost outperforms the other algorithms examined, with accuracy, precision, recall, and AUC-ROC values of 0.89, 0.92, 0.85, and 0.89 respectively. This demonstrates the model's robustness in predicting cardiovascular risk.

## Feature Importance

An additional analysis is conducted to identify the most critical features in the dataset. The feature importance plot reveals that age, education, prevalent hypertension, and daily cigarette consumption are the top predictors of cardiovascular risk. This insight can be utilized to identify high-risk individuals and implement preventive measures.

## Conclusion

In conclusion, this project showcases the potential of machine learning techniques in accurately predicting cardiovascular risk using the Framingham Heart Study dataset. The developed machine learning model can assist healthcare providers in identifying individuals at high risk for cardiovascular disease and taking preventive actions to mitigate that risk. Early prediction of cardiovascular risk can facilitate timely interventions and improve patient outcomes.
