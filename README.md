# datafun-06-eda

Specification for Project 6 EDA Notebook
Overview
Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

Objective
Perform and publish a custom EDA project to demnostrate skills with Jupyter, pandas, Seaborn and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.

Explore Datasets
Choose a dataset for analysis. You will want a known, clean dataset. Cleaning data can run 60-80% of the project (or more) - you don't need to demonstrate cleaning skills for this project.
The recommneded approach is to select one of the other pre-installed datasets in Seaborn. You can view a list of the Seaborn datasets in the first link below. The additional links offer a range of options.

List of Seaborn Datasets Installed
UCI Machine Learning Repository
Kaggle Datasets
Data.gov
Google Dataset Search
You may use your own data if you have permission and there is no confidential information included. Be careful with your data selection and ensure you have rights to use the content.

## Dataset description
This EDA will analyze the "mpg" dataset from the seaborn library. This database looks at vehicles and several variables that may contribute to its mpg (miles per gallon). These variables include cylinders, horsepower, engine displacement, and weight. This database shows several types of vehicles and some of their specs.
This database can be accessed with the following link:
https://github.com/mwaskom/seaborn-data/blob/master/mpg.csv 


## Clone repo from GitHub website
git clone https://github.com/carlosmontoya3/datafun-06-eda

## Creat project virtual environment
python3 -m venv .venv

## Activate Environment
source .venv/bin/activate

## Install packages
python3 -m pip install jupyterlab pandas pyarrow matplotlib seaborn


## Run pip freeze and redirect the results (>) into requirements.txt
python3 -m pip freeze > requirements.txt

## Push to GitHub
git add .
git commit -m "commit"
git push -u origin main
