# Ames-Housing-Prediction
This project aims to predict the sale price of houses in Ames, Iowa using different regression techniques. The exploratory analysis of the housing data can be found in the 'Exploratory Analysis' notebook, and the data preprocessing and prediction methods can be found in the 'Data Cleaning & Prediction' notebook.

## Data
The data used for this project is the Ames Housing dataset, collected by Dean De Cock, which contains data describing sales of individual residential properties in Ames, Iowa from 2006 to 2010 (http://jse.amstat.org/v19n3/decock.pdf). Furthermore, no authorisation is necessary to use the dataset - it has been shared to freely use, as stated by Dean (this means no access restrictions). A workspace has also been created to neatly organise the project into different repositories, such as one for data and another for documentation.

Four different files have been provided (from Kaggle) to assist with the project in an easy-to-manipulate format - train.csv, test.csv, data_description.txt and sample_submission.csv. The total space of these four files is approximately 1MB. The dataset's 2930 observations have been separated into training and testing csv files, with the training file used to train the model and the testing file to test the model's performance (so there is no need to sample a test set). The txt file contains full descriptions of each feature/attribute, slightly modified from Dean's descriptions to match the column names used. The other csv file contains a benchmark submission to help understand what is required as output from the model.

## Getting Started
Open the 'Exploratory Analysis' notebook to check out the data collected. A couple of different data stories have been compiled to help better understand the data for when it is cleaned and processed. The 'Data Cleaning & Prediction' will show the steps taken to clean the data and remove unwanted observations/features, and also the prediction results for a couple different regression estimators.

## Built With
* Scikit-learn, Pandas, NumPy
* Jupyter Notebook
