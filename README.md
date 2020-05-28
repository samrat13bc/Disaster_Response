# Disaster_Response
Disaster Response Pipeline Project

Intro Pic
![intro](https://user-images.githubusercontent.com/65721102/83110162-45a85680-a0e0-11ea-8fd2-23799c39ef94.png)


Table of Contents

Description

Getting Started

Dependencies

Installing

Executing Program

Additional Material

Authors

Acknowledgement

Screenshots

Description
This Project is part of Data Science Nanodegree Program by Udacity in collaboration with Figure Eight. The initial dataset contains pre-labelled tweet and messages from real-life disaster. The aim of the project is to build a Natural Language Processing tool that categorize messages.

The Project is divided in the following Sections:

Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure

Machine Learning Pipeline to train a model able to classify text message in categories

Web App to show model results in real time.

Getting Started

Dependencies:
Python 3.5+ (I used Python 3.7)

Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn

Natural Language Process Libraries: NLTK

SQLlite Database Libraqries: SQLalchemy

Web App and Data Visualization: Flask, Plotly

Installing

Clone this GIT repository:

git clone https://github.com/samrat13bc/Disaster_Response

Executing Program:

Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/messages.csv data/categories.csv data/DisasterResponse.db

To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

Run the following command in the app's directory to run your web app. python run.py

Go to http://0.0.0.0:3001/


Additional Material

In the data and models folder you can find two jupyter notebook that will help you understand how the model works step by step:

ETL Preparation Notebook: learn everything about the implemented ETL pipeline

ML Pipeline Preparation Notebook: look at the Machine Learning Pipeline developed with NLTK and Scikit-Learn

You can use ML Pipeline Preparation Notebook to re-train the model or tune it through a dedicated Grid Search section. In this case, it is warmly recommended to use a Linux machine to run Grid Search, especially if you are going to try a large combination of parameters. 

Using a standard desktop/laptop (4 CPUs, RAM 8Gb or above) it may take several hours to complete.


Authors

Samrat Nilesh


Acknowledgements

Udacity for providing such a complete Data Science Nanodegree Program
Figure Eight for providing messages dataset to train my model

Screenshots:

This is an example of a message you can type to test Machine Learning model performance
Sample Input
![sample_input](https://user-images.githubusercontent.com/65721102/83110577-e7c83e80-a0e0-11ea-832c-c50177bba3cf.png)

After clicking Classify Message, you can see the categories which the message belongs to highlighted in green
Sample Output
![sample_output](https://user-images.githubusercontent.com/65721102/83110637-fd3d6880-a0e0-11ea-9b67-48e767048fd8.png)


The main page shows some graphs about training dataset, provided by Figure Eight
Main Page
![main_page](https://user-images.githubusercontent.com/65721102/83110688-11816580-a0e1-11ea-8098-519009c171aa.png)

