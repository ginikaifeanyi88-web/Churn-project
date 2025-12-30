# Churn-project

## Table of Contents 
1. Project Description
2. Resources
3. Installation and Experiment Run

## Project Description

This project was done for general practice and play. The Churn dataset was readied for prediction by the logistic regression model. Several columns contained null values including gender, dependents, city, and days since last transaction. Using the pandas dataframe .dropna() method, all rows  with null values were dropped. Next all categorical columns were encoded into numerical variables. Gender was encoded using label encoding and occupation using one-hot encoding. The difference is that the former keeps the variable contained in a single column and the latter encodes it into several. Next the data was split into features (x) and target data (y) and then subsequently into 80% training data and 20% testing data. The model performed well at 81% accuracy thanks to careful preprocessing.

## Resources 
To run this project the you will need:
1. The chrurn(in) dataset.
2. Python
3. Anaconda Navigator to launch and run Jupyter Notebook.

## Installation and Experiment Run
1. If you have not already, sign up for an Anaconda account [here](https://www.anaconda.com/download).
   1. Click Get Started and enter in your details.
   2. After logging in, download the version for your operating system (Windows, MacOs, Linux). There are plent of YouTube videos to help you on this step.
   3. Open the app and launch Jupyter Notebook.
2.  Download the Tyler the Creator dataset in the Dataset subfolder and than download the Jupyter notebook in the Jupyter Notebook subfolder.
3.  Place both files in the same folder within your computer.
4.  In Jupyter Notebook, look for the new folder you created, click it, and open the Jupyter Notebook file.
5.  Run the program step by step and read the Project description (in Research paper subfolder) to confirm results.
