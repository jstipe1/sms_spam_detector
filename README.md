# sms_spam_detector
Module_21_Challenge

__Purpose__: In this Challenge we are refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, a  Gradio app is created to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance
  
    
&nbsp; &nbsp; __Step 1__: Create the SMS Classification Function  
&nbsp; &nbsp; __Step 2__: Create the SMS Prediction Function   
&nbsp; &nbsp;__Step 3__: Create the Gradio Interface Application

__Intalls__: A number of installations are needed (and provided) to run the code necessary to complete this project  
  
import pandas as pd  
from sklearn.model_selection import train_test_split  
from sklearn.pipeline import Pipeline  
from sklearn.feature_extraction.text import TfidfVectorizer  
from sklearn.svm import LinearSVC

[Python Documentation] (https://docs.python.org/)  
[Jupyter Notebook Documentation] (https://jupyter-notebook.readthedocs.io/)  
[sklearn Documentation]  (https://scikit-learn.org/0.21/documentation.html)  

__Resources__:  
[Xpert Learning Assistance]   
[README.md formatting] (https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796)  
