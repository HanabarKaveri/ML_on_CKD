# ML_on_CKD
### This project is made up of Three parts.
   - Data-Preprocessing
   - EDA
   - Applying SVM and Bagging methods
### About Data Description
#### Original dataset link: https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease
#### Dataset
   - Dataset contains 24 features and 400 samples.
#### Features
#####  age	  -	age	
#####  bp	  -	blood pressure
#####  specific gravity	  -	specific gravity
#####  albumin	  -     albumin
#####  sugar	  -	sugar
#####  rbc	  -	red blood cells
#####  pus cell	  -	pus cell
#####  pus cell clumps	  -	pus cell clumps
#####  bacteria	  -	bacteria
#####  blood glucose random        -	blood glucose random
#####  blood urea	  -	blood urea
#####  serum creatinine	  -	serum creatinine
#####  sodium	  -	sodium
#####  potassium	  -	potassium
#####  hemoglobin	  -	hemoglobin
#####  packed cell volume	  -	packed cell volume
#####  white blood cell count	  -	white blood cell count
#####  red blood cell count	  -	red blood cell count
#####  hypertension	  -	hypertension
#####  diabetes mellitus	  -	diabetes mellitus
#####  coronary artery disease	  -	coronary artery disease
#####  appetite      -	appetite
#####  pedl edema	  -	pedal edema
#####  anemia	  -	anemia
#####  classification      -	class
### Methodology
The methodologies used are preprocessing, exploratory data analysis and machine learning. The data preprocessing involves handling missing values and converting categorical data into numerical format. Exploratory data analysis is conducted to understand the relationships between different features and their impact on chronic kidney disease (CKD). Machine learning models, such as Support Vector Machine (SVM) and Bagging Classifier, are applied to the dataset for predicting CKD. These methodologies collectively aim to gain insights and predict the occurrence of chronic kidney disease based on clinical indicators.
### Model Description
Various models are used for analyzing and predicting chronic kidney disease (CKD). It includes the application of machine learning.The models include Support Vector Machine (SVM), Bagging Classifier. The SVM model is optimized using GridSearchCV to find the best parameters, and its performance is evaluated using accuracy, F1 score, precision, sensitivity, and specificity. The Bagging Classifier is used with varying numbers of estimators, and its performance is also evaluated. These models are designed to predict the occurrence of chronic kidney disease based on patient’s health profile.
