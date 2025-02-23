# Titanic-Survival-Prediction-Model

A Random Forest Classifier pipeline that predicts the survival of a boarder on the titanic ship based on the attributes of the person such as their age, sex, passanger class etc. using scikit-learn.  

The primary goal was to obtain experience on data mining, feature engineering, model selection, hyperparameter tuning and other essential practices required to train a efficient machine learning model.  

The score I got on the submission is decent but certainly can be improved. However, I think the main purpose of working on dummy datasets is to learn stuff from them, not to master that dataset, so I am going to conclude the work on this dataset here.  

![Image](https://github.com/user-attachments/assets/16443f9e-ee18-49d3-a14d-48fdd9cc5089)

[KAGGLE Titanic-Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview)

# How to Setup
Open a terminal and navigate to the project folder  
Run the following command to make a virtual environment using pip-  
`python -m venv venv`  

To activate the venv, run-
Linux & macOS- `source venv/bin/activate`  
Windows - `venv\Scripts\activate`  

To install the required dependencies, run-  
`pip install -r requirements.txt`  

Now you are all setup and can run any notebooks in the notebooks folder or you can directly import the pipeline.pkl and run it to process and predict the kaggle titanic data.  
Just keep in mind to select the kernel as the venv :)
