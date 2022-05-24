# Ecommerce_analysis
## Project description
The goal is to segment users based on their consumption profile (purchase history), research data and give recommendations for users personalization. 
## Dataset description
Dataset includes purchase history over a period of 01/10/2018-31/10/2019. Datasets consists of 6377 lines, without omission, including following information:
 - Purchase date (int)
 - User Id (object)
 - Order Id (object)
 - Purchase name (object - in no particular format)
 - Number of purchases (int)
 - Cost per 1 purchase (int)
![Dataset sample](https://github.com/kseniavarakina/Ecommerce_analysis/blob/master/dataset_head.png) 
## Used libraries
| Task description       | Used library | 
| -----------------------|:-----------------------:| 
| Lemmatization          | regex                   | 
| Categorization         | gensim, SnowballStemmer | 
| Data analysis          | pandas                  |
| Data visualiation      | matplotlib, seaborn     |
| Hypothesis validation  | scipy                   |
