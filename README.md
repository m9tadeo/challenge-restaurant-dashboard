# Description

This project is aimed at using the [TripAdvisor Restaurants Info for 31 Euro-Cities](https://www.kaggle.com/datasets/damienbeneschi/krakow-ta-restaurans-data-raw) dataset to find insights for a fictional European travel agency to help them grow their business.

A dashboard is created from the dataset to help travel agents make recommendations to their clients on the best food destinations while they are traveling in and around Europe.

# Getting Started

The dataset is available from `kaggle` website:  

[TripAdvisor Restaurants Info for 31 Euro-Cities](https://www.kaggle.com/datasets/damienbeneschi/krakow-ta-restaurans-data-raw)  

You will also need the following:

•[Python 3.x](https://www.python.org/downloads/)  
•[pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)  
•[Microsoft Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

# Installation

This step by step guide will get you up-and-running on your local machine.

1. Create and activate your virtual environment. I used [anaconda](https://www.anaconda.com/products/distribution) to create my virtual environment.  

    `conda create -n <yourenvname> python=<x.x> anaconda`  
    `conda activate <yourenvname>`  
    
    **yourenvname** is your virtual environment name and **x.x** is your python version

2. Install pandas library

    `conda install pip`  
    `pip install pandas`  

3. Open the notebooks in a code editor of your choice running on the virtual environment you just created.  

# Pipeline

A. Preprocessing  

1. Clean raw dataset (fill-in empty or NaN values, remove some characters)  
2. Transform `Price Range` column values  

B. Best Restaurants  

1. Filter dataset for highest Rating (5.0)  
2. Create `Dashboard Review` column extracted from `Reviews` column  

# Visuals

### Primary Dashboard

![Restaurants of Europe](image.jpg)  

### Best Restaurants Dashboard

![Best Restaurants](image.jpg)  

# Timeline

Project Start: 26 January 2023  
Project End: 3 February 2023  

# Next Steps

•Refine dataset further by splitting values of columns with multiple entries/values per row (`Cuisine Style` and `Reviews`)  
        - turn csv file into a database with separate tables for `Cuisine Style` and `Reviews` columns respectively  
        - connect to main table via a unique id  
        - use SQL join to generate tables with single entry/value for each column to use in Power BI dashboard  
        
•Use geocoding to identify latitude and longitude values for each restaurant and display a more accurate map in the dashboard  

# Personal Situation  

My name is [Marlon Tadeo](https://github.com/m9tadeo) and I am currently a Data Analyst trainee at BeCode Ghent. You can reach me at `m9tadeo@gmail.com`.
