# Women's E-Commerce Clothing Reviews

In this project, we'll be using NLP clustering to find out some good information about cusomers reviews to take advantage of e-commerce.

## About the company
Unknown company who is interested in e-commerce, especially women’s clothing trade needs help to get the best information about women's clothing sales. We want to rely on sources that confirm to us the target group of women in relation to their age and clothing choices. Therefore, we decided to rely on customer evaluation for a group of websites, and based on the results, we will discover:

* What is the best selling clothing? 
* What is the most type of clothes that has more positive reviews?
* At which age womens buy clothes most? 


## Aim and Objectives:
* Predicting the best recommended product based on customers reviews. 

## Data Description
This is a Women’s Clothing E-Commerce dataset revolving around the reviews written by customers. Its nine supportive features offer a great environment to parse out the text through its multiple dimensions, the source of dataset from [kaggle](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews/metadata) and which consists of
* 23486 rows 
* 10 feature 

#### Each row corresponds to a customer review, and includes the variables:
| Field Name            | Description                                                                                                |
|-----------------------|------------------------------------------------------------------------------------------------------------|
|Clothing ID            | Integer Categorical variable that refers to the specific piece being reviewed                              |
|Age                    | Positive Integer variable of the reviewers age                                                             |
|Title                  | String variable for the title of the review                                                                |
|Review Text            | String variable for the review body                                                                        |
|Rating                 | Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best    |
|Recommended IND        | Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended |
|Positive Feedback Count| Positive Integer documenting the number of other customers who found this review positive                  |
|Division Name          | Categorical name of the product high level division                                                        |
|Department Name        | Categorical name of the product department name                                                            |
|Class Name             | Categorical name of the product class name                                                                 |


## Libraries:

* pandas 
* numpy 
* seaborn 
* pandas profiling 
* plotly express 
* matplotlib pyplot 
* sklearn model
* ipywidgets
* collections 
* wordcloud 
* warnings

## Tools:

* python
* jupyter notebook
* PowerPoint
