# COVID-19-MLModels-LaboratoryTest
In this work, its shown that it is possible to predict the test result for SARS-CoV-2 based on the results of laboratory tests commonly collected for a suspected COVID-19 case by analyzing a sample of 5644 patients of which 558 tested positive for SARS-CoV-2 from the Hospital Israelita Albert Einstein.

## Installation and steps to run the app:
- cd Deployment-flask
- python3 —version -> make sure python version is 3.*
- pip3 install pipenv -> virtual enviornment
- pipenv shell -> activate the virtual env
- pipenv install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy sklearn -> install the relevant libraries in your virtual env
- python3 -> go python shell
- from app import db 
- db.create.all() -> creating the sqlite database

## data set:
https://www.kaggle.com/einsteindata4u/covid19
