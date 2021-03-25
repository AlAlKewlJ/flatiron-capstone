# Flatiron-Capstone

## Repository Navigation

The final notebooks are found in the main folder. The notebooks are named:

1. api_call.ipynb (code used to collect the data)
2. Cleaning and EDA.ipnyb (code for data cleaning and exploratory data analysis)
3. Model.ipynb (code used to create the model)

The csv used for modeling is called:

1. dfs4.csv

Within the main folder, you will also find two subfolders that contain files used to create the final notebooks and final dataset:

1. Data
2. Working Notebooks


## Business Problem

According to the National Center for Charitable Statistics there are 1.54 million nonprofit organizations in the United States. These nonprofits work on various issues from education, health and art, to advocacy organizations and direct service. In 2019, the Charities Aid Foundation ranked the United States as the most  generous country in the world in their World Giving Index over the past 10 years. The World Index Giving Score is calculated by using three key measures, 1) Helping a Stranger 2) Donating money and 3) Volunteering time. In the past year, the United States and the world have dealt with challenging times. From dealing with the COVID-19 pandemic to more visibility of police brutality towards the black community and increasing hate crimes towards the API communities, Americans are moving into action. 

Before giving of your time and money, it is important to do research. However, reading mission statements and vision statements on organization websites can be time consuming. Additionally, finding aggregated information about nonprofit organizations can come in a format that may not be extremely interpretable. If you were data savvy you could always do an API call but these have their limitations and are often behind a paywall. If you are able to get over those hurdles, you will find that not all organizations have a rating. For instance, Charity Navigator (the API I used) has over 1.5 million Nonprofits listed but only a few hundred thousand with actual ratings. I want to create a model that can predict whether or not a nonprofit organization will get a financial rating or a low financial rating.  

## Data

The data was collected through API calls from Charity Navigator. The original dataframe collected, contained over 10,000 entries and 26 columns. The dataframe I ended with consisted of over 10,000 entries and 77 featyres. The datatypes consist of a combination of float64, and object64. 

## Data Science Process Steps and Reproduction

Once I collected my data from Charity Navigator, I began to check the datatypes, identified the Nan values and began cleaning my data. Cleaning my data was an interative process and found myself going back and cleaning throughout the project. With 'clean' data I proceeded to do some EDA and looked at rating distribution and created histograms to visualize that. Once I completed my EDA I proceeded to create features for my model including dummying variables. I used this new dataframe to build my base model using Logistic Regression and Random Forest.   

## Link to Presentation 

https://docs.google.com/presentation/d/1G3aPIm-rO3XOIIkcELFjyZNuvXmGRz0MSKAaxeaYh9s/edit?usp=sharing

## Link to resources

Charity Navigator 
