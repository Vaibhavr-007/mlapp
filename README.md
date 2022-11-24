# Heart Disease Prediction
The term “heart disease” refers to several types of heart conditions. The most common type of heart disease in the United States is coronary artery disease (CAD), which affects the blood flow to the heart. Decreased blood flow can cause a heart attack.


Cardiovascular diseases are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide. Early detection, and managment of cardiovascular diseases can be a great way to manage the fatality rate associated with cardiovascular diseases, and this is where a machine learning model comes in

## We will use the following steps to predict the Heart Disease
* Understanding the Problem
* Reading and understanding the data
* Exploratory Data Analysis and visualisation
* Modeling
* Generate Insight

## Objective
In this notebook we are going to perfrom some analysis to discover differnt insights about the Heart disease and develop different ML models(Logistic Regression,Decision Tree,Random Forest etc) to predict the chances of Heart Disease based on some relevant features.

## Dataset
The dataset is taken from kaggle. Source of the dataset - [Heart disease prediction](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

There are 13 features/attributes in the dataset, which are described below.

* age: age in years
* sex: sex (1 = male; 0 = female)
* cp: chest pain type
    * Value 0: typical angina
    * Value 1: atypical angina
    * Value 2: non-anginal pain
    * Value 3: asymptomatic
* trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* chol: serum cholestoral in mg/dl
* fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg: resting electrocardiographic results
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
* thalach: maximum heart rate achieved
* exang: exercise induced angina (1 = yes; 0 = no)
* oldpeak = ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
    * Value 0: upsloping
    * Value 1: flat
    * Value 2: downsloping
* ca: number of major vessels (0-3) colored by flourosopy
* thal: Thalessemia
    * 0 = normal
    * 1 = fixed defect
    * 2 = reversable defect
* condition: 0 = no disease, 1 = disease --> ####target variable



## Conclusion
So in this notebook we have developed a different machine learning model to predict the chances of having heart disease or not and seen that Random forest classifier had the highest accuracy compared to other models.
