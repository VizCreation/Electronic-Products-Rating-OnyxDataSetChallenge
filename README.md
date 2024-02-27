# Electronic-Products-Rating-Dashboard-Onyx-DataSet-Challenge
This is a Dataset challenge held by OnyxData In Feb 2024. The aim of the challenge is to showcase the best visualisation dashboard that will help the business leverage the data and transform their business. The dataset consist of details of Electronic Products Rating and Reviews from customers.

## Problem Statement
1. Which brands have the highest average customer satisfaction, and how does it vary across different product categories?
2. How do product features (like color or dimensions) influence reviews and ratings?
3. What is the relationship between product ratings and recommendation status?

## Data Sourcing
The data set is given by Onyx Data for the Data Challenge.
Link: (https://onyxdata.co.uk/data-dna-dataset-challenge/datadna-dataset-archive/)


## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI. Some of the applied steps include:
* Removing duplicate rows
* Renaming Column headers and table values to a more suitable and readable header (eg. 'reviews.doRecommend' is renamed to 'Recommend?' and cell values are changed from 'True/False' to 'Yes/No'.)
* Extracting Date from DateTime column for 'DateAdded' Product and 'Date Updated' Product as the time is not crucial in this visualisation

## Data Visualisation

This Dashboard was created for the Challenge Project. <br>
<br>Users can use the slicers at the left column to choose their desired brand(s) that they wish to analyse. Else by default, the dashboard selects all brands for analysis.
