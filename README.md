# heart-disease-classification
Predicting heart disease using machine learning
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes. We're going to take the following approach:

Problem definition:-
  Data
  Evaluation
  Features
  Modelling
  Experimentation
  
1. Problem Definition:-
In a statement,Given clinical parameters about a patient, can we predict whether or not they have heart disease?

2. Data:-
The original data came from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease

There is also a version of it available on Kaggle. https://www.kaggle.com/ronitf/heart-disease-uci

3. Evaluation:-
If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

4. Features:-
  Create data dictionary*
  age age in years
  sex (1 male; 0= female);
  cp chest pain type
  trestbpsresting blood pressure in mm Hg on admission to the hospital)
  cholserum cholestoral in mg/dl
  fbs (fasting blood sugar> 120 mg/dl (1 = true; 0 = false)
  restecgresting electrocardiographic results
  thalachmaximum heart rate achieved Q
  exangexercise induced angina (1 = yes: 0 = no)
  oldpeakST depression induced by exercise relative to rest
  slopethe slope of the peak exercise ST segment
  canumber of major vessels (0-3) colored by flourosopy
  thal3 = normal; 6 = fixed defect; 7 = reversable defect
  target1 or 0
