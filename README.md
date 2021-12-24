# Who are the important customers? NLP-project

## About Company
A company interested in e-commerce, especially women’s clothing trade. We want to rely on sources that confirm to us the target group of women in relation to their age and clothing choices. Therefore, we decided to rely on customer evaluation for a group of websites, and based on the results, we will discover:
* What is The average age for which you pay the most?, What kind of women's clothing is bought the most? Positive/Negative Reviews for what type of clothes?


## Aim and Objectives:
* Predict what is the best selling product

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
