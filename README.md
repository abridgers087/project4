# Predicting Rat Activity in New York City using Machine Learning (Project 4)
You can download the data I used for this project here: [Link to Data](https://drive.google.com/file/d/1G65seShaKqzOTbaGDS8eYQ0COMmqNSZf/view?usp=drive_link)</br>
The updated dataset can be downloaded from: [Updated Dataset Link](https://dev.socrata.com/foundry/data.cityofnewyork.us/p937-wjvj)</br>

Welcome to my Project 4 repository! This repository contains the code, data, and documentation for my in-depth data analysis project. I focused on predicting rodent activity in New York City based on NYC Open Data's "Rat Data". I utilized deep learning techniques to analyze a dataset of rat complaints and mitigation efforts, aiming to determine which locations were likely to experience rat activity.</br>

In this project, I adopted a systematic approach to data exploration, cleaning, preprocessing, and modeling. I examined the characteristics of individual features closely, executed necessary preprocessing steps, and implemented a deep learning model with the Hyperband optimization technique to identify the best model hyperparameters. The detailed comments and annotations found in the notebooks in the 'Research' folder offer insights into my methodology, making this repository a valuable resource for data science enthusiasts, researchers, and machine learning practitioners.</br>

# Project Data

Below is a brief description of the main notebook in this repository and a list of Python imports needed to execute the code. I hope you find this repository both insightful and informative.</br>

<b><i>NYC Rats Final NN with Prediction Code.ipynb</b></i>: This is where I cleaned the data, built the model, tested, and optimized. This file also includes a section that cleans new datasets from MongoDB, loads the prediction model, and makes predictions on the new data.</br>

<b><i>Mongo Data Steps.txt</b></i>: This file contains a list of the steps I took to load the CSV file into MongoDB, including data type changes, etc.</br>

Python Imports Needed:
- [requests](https://pypi.org/project/requests/)
- [json](https://docs.python.org/3/library/json.html)
- [pandas](https://pandas.pydata.org/)
- [PyMongo](https://pymongo.readthedocs.io/en/stable/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/)
- [keras_tuner](https://keras.io/keras_tuner/)

# Notes on Notebooks in 'Research' folder:
<b><i>NYC Rat Data Collection Notebook</b></i>: This was the initial notebook where I analyzed various parts of the dataset to determine its fit and scope for the project. Notes are included.</br>
<b><i>NYC Rat Data Test Optimization</b></i>: This is the initial test file for the ML model optimization tests (adding, removing, changing variable set for the model). Test notes are included within the notebook.</br>

Some of the key components of these notebooks include:

- Detailed examinations of the distributions and characteristics of individual features, which helped identify patterns, outliers, and potential data quality issues.
Preprocessing steps, such as encoding categorical variables, transforming numerical features, and scaling the data, which enhanced the performance of the machine learning models.</br>

- Implementation and tuning of a deep learning model using the Hyperband optimization technique, aimed at finding the best model hyperparameters for optimal predictive performance.</br>

- Comprehensive notes and comments that provide context for the analysis, highlight key findings, and suggest potential avenues for future research.</br>

- The files serve as a complete record of my data analysis workflow, capturing the entire process from initial data exploration to model evaluation. They can be referenced for further analysis and experimentation or adapted to other datasets and research questions.</br>

# Other Folders
- <b><i>Resources</b></i>: Project Data Dictionary from NYC Open Data, Project Proposal, User Guide to "Rat Data" from NYC Open Data.
- <b><i>Results</b></i>: Hyperband test results folder.
- <b><i>Model</b></i>: Saved ML Model (can be loaded with load_model from tensorflow)
