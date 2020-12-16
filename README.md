# Ames Housing Data and Kaggle Challenge


### Primary Learning Objectives

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

I was tasked with creating and iteratively refining a regression model based on this dataset. My model was to predict the price of a house at sale and provide buisness insights through reporting and presentation.

Secondly, I was given the opportunity to practice the following skills by participating in a Kaggle competetion:
- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science



### Problem Statement

TCB General Contractors is a general contracting company in Ames Iowa that oversees and executes home construction projects.

The Board of Directors at TCB General Contractors are implementing a new marketing strategy to increase the company's revenue. 

To implement this new strategy, they want to discover which of their services are most impactful on the future value of the home. 

This information will be used to promote specific renovations in their upcoming marketing plan. 

My task is to discover the services that most dramatically increases the sales price of the home.



### Methodology

The predicted the response for my project is the variable Sale Price.

As the output of my project is the numeric 'Sale Price', I used a linear regression modeling algorithm to evaluate the Ames Housing Dataset.

The success of my model was evaluated by the regression metric 𝑅2. I used R2 as it is easily interpretable and does not depend on the scale of "Sales Price".



### Findings

Top High Value Renovations:
-Kitchen Renovation +$12,739
-Above Ground Additions +$11,083
-Garage Addition +$8,771/car. 

Low Value Renovations: 
-Wood deck +$1800
-Basement Renovation +$2523

Value of bathroom addition is dependant on the amount of rooms in home.



### Conclusion & Reccomendations

Focus new marketing campaign around kitchen renovation, above ground additions, and garage addition as they generally add the most value to a home. 

I would not focus on the addition of a wood deck or basement refinishing as the cost of these projects are more than the value added to the home.

Given similar data I do think this model will generalize to other cities.



### Possible Items to Further Investigate:

I would want to look into how specific materials within each renovation adds value to each project. This could be used as an upsale tool for TCB contracting.



### Directory Structure
```
|__ code
   |__ 01_Project 2 Final Notebook.ipynb   
   |__ 02_EDA_Cleaning_Preprocessing_and_Feature_Engineering.ipynb   
   |__ 03_EDA_Cleaning_Feature_Engineering_Kaggle_Submissions.ipynb   
|__ data
   |__ train.csv
   |__ test.csv
   |__ kaggle-submissions
            |__ my_submission_1.csv
            |__ my_submission_2.csv
            |__ my_submission_2.1.csv
            |__ my_submission_3.csv
            |__ my_submission_3.1.csv
            |__ my_submission_4.csv
            |__ my_submission_4.1.csv
|__ images
   |__ sales_price_boxplot.png
   |__ all_relevant_features_heatmap.png
   |__ top_relevant_features_heatmap.png
   |__ dog_construction.png
   |__ residual_hist.png
   |__ attribute_histogram_plots.png
|__ presentation.pdf
|__ README.md
```
