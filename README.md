# Electronic-Products-Rating-Dashboard-Onyx-DataSet-Challenge
This is a Dataset challenge held by OnyxData In Feb 2024. The aim of the challenge is to showcase the best visualisation dashboard that will help the business leverage the data and transform their business. The dataset consist of details of Electronic Products Rating and Reviews from customers.

## Problem Statement
1. Which brands have the highest average customer satisfaction, and how does it vary across different product categories?
2. How do product features (like color or dimensions) influence reviews and ratings?
3. What is the relationship between product ratings and recommendation status?

## Data Sourcing
The data set is given by Onyx Data for the Data Challenge.
Link: (https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/files/14420272/Onyx.Data.-DataDNA.Dataset.Challenge.-.Electronics.Product.Data.Ratings.-.February.2024.xlsx)


## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI. Some of the applied steps include:
* Removing duplicate rows
* Renaming Column headers and table values to a more suitable and readable header (eg. 'reviews.doRecommend' is renamed to 'Recommend?' and cell values are changed from 'True/False' to 'Yes/No'.)
* Extracting Date from DateTime column for 'DateAdded' Product and 'Date Updated' Product as the time is not crucial in this visualisation

## Data Visualisation

This Dashboard was created for the Challenge Project. <br>
Users can use the slicers at the left column to choose their desired brand(s) that they wish to analyse. Else by default, the dashboard selects all brands for analysis. This Dashboard also includes a table with the details of the products, ratings and text reviews. Users can scroll through the table if they wish to drill down to find out more about the written reviews.


**Main Dashboard**
![Electronics Dashboard Main](https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/assets/157504708/b6ecd747-bb65-4d96-a830-02f8dea414f7)

**Dashboard with Tooltip Details**
![Electronics Dashboard2](https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/assets/157504708/9b67517d-28d1-4b1a-85b1-d5d93f019845)

**Table Scroll Bar**
![Dashboard Table Scroll](https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/assets/157504708/a7c6fe09-4446-44c3-bef7-e5188c023e4e)


## Findings/Conclusion
1. The top 3 brands with the highest ratings of 5 are Kicker, SVS and Clarity-Telecom. However, upon closer analysis the review count for these brands are quite low at 3,1 and 11 respectively. The low rating count is not a good reflection of how good a product is. Thus, I have created another horizontal bar chart that shows the 'Brand Ranking by Sum of Ratings'. This will gives a better indication of how popular a product is. Based on this Chart, the top 3 brands with highest ratings are Logitech, Sony and Microsoft.
    
2. Based on the 2 line graphs 'Rating by Color' and 'Rating by Dimension', it seems like the product features such as Colors and Dimension doesn't have much influence on the ratings as regardless of the features, the ratings range from 3.5 - 5.
     
3. Usually for higher product ratings, customers will tend to recommend others to purchase the products. Hence, it is crucial for companies to try to secure good ratings from customers.
