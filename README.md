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
<br>Users can use the slicers at the left column to choose their desired brand(s) that they wish to analyse. Else by default, the dashboard selects all brands for analysis.

![Electronics Dashboard Main](https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/assets/157504708/b6ecd747-bb65-4d96-a830-02f8dea414f7)

![Electronics Dashboard2](https://github.com/VizCreation/Onyx-DataSet-Challenge-Electronic-Products-Rating/assets/157504708/9b67517d-28d1-4b1a-85b1-d5d93f019845)


## Findings/Conclusion
1. Most subscribers (69%) are willing to pay for the courses, compared to 31% who are taking only the free courses. Hence, it seems that this business model is sustainable as there are moajority of people paying than taking free courses and the earnings are sufficient to cover the course of running the site.

2. * Currently there are only 4 categories of courses (Web Development, Graphic Design, Business Finance and Musical Instrument), Udemy may consider expanding the categories to include others such as language, personal improvement, grooming etc.
   * Also, majority of subscribers (71%)  are interested in Web development courses, hence Udemy may consider including more such courses or add on intermediate or higher level web development courses. 
   * Lastly, based on the bottom middle bar chart, 61% of the total sales come from the courses that charge between $151-$200. It shows that people are willing to pay for the courses as long as the content is of their interest and beneficial to them. <br>

3. Based on the 'Course Ranking by Sales' bar chart (bottom rightmost chart), Web Development and Musical lesson on Piano are one of the more sellable courses.
