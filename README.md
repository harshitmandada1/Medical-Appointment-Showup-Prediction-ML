
  # Medical Appointment ShowUp or NoShowUp Predictions
  
                              
  ## Objective  
  
  
  The objective of this repository is to produce an best model to predict an appointment's no-show, given a patient. The data set shows information of appointments in public hospitals in Vitoria, Espirito Santo, Brazil.
  
  ![GitHub Logo](/Images/NoShowUp.jpg)
  




  ## The following steps are included:

  * Univariate Analysis (with Feature Engineering) and Exploratory Data Analysis

  * Significant Featuring (using corelation matrix and VIF)

  * Machine Learning Modelling with hyperparameter tuning
    * Logistic Regression
    * Support Vector Machine
    * Random Forest
  
  * Model Analysis
 
 ## Version 2.0
  Added Model Interpretability 
    * Permutation Importance.
    * Partial Dependence plots
    * SHAP Values
  
## *Conclusion*
  
Feature named MissedAppointments which was not present in dataset initially,After figuring it out, found it has the most corelated feature to the dependent variable, it makes sense that behavior of previous instances is helpful to predict the current instance whether the patient is going to showup or not. Finally, Able to predict with 92% Accuracy

## *License*
Copyright 2020 Satya Ikyath Varma Dantuluri

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
