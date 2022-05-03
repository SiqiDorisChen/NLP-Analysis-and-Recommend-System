# Clothing-data-NLP-Analysis-and-Recommender

## Description
This is a course project of Analyzing Unstructured Data class at UCSD.

This projected developed using Python 3.8. 

In this project, I conduct analysis on the rating and fit of customers based on the e-commerce clothing data collected from RentTheRunway.com. The model results show that review texts could largely improve the performance of classifiers which only includes customer demographics and body measurements. Other than that, word embedding models such as Skip-gram and CBOW which focus on learning from context perform best among a series of text mining models. Moreover, I developed a recommender to return recommend items for a given user_id. 

## Data
`renttherunway_final_data.json`

The raw data collected from RentTheRunway.com, containing 192,544 records from 105,508 users regarding 5,850 items.

To download this file, please go to https://www.dropbox.com/s/9omw6s9bh8vxkgu/renttherunway_final_data.json?dl=0.

`glove.6B.100d.txt`

The corpus which is used to train the Glove model (with the embedding dimensions of 100).

To download this file, please go to https://www.dropbox.com/s/sc5uzmrcype7udr/glove.6B.100d.txt?dl=0 or refer to https://nlp.stanford.edu/projects/glove/.

## Files
`NLP Analysis and Recommend System.ipynb`

The code containing all the works mentioned in our report.

`Technical Paper.pdf`

The final report which includes detailed process.

## Recommended items for users (Demo)
Here is a recommendation for user 420272

item id_Item & Item rented_for reason 

2732613 shirt date, everyday, party, other, work 

925104 dress wedding, everyday, party, vacation, other

1006590 dress date, party, wedding 940419 dress date, wedding, everyday, party, formal affair 

962489 dress date, everyday, party, vacation, other, work 

1601603 dress date, wedding, party, formal affair, other 

2375866 skirt vacation, party, everyday 

2363191 jumpsuit date, everyday, party, formal affair, vacation 

1635675 dress date, wedding, everyday, party, formal affair

2211789 romper vacation, party, everyday, other

## Reference
Rishabh Misra, Mengting Wan, Julian McAuley (2018). *Decomposing fit semantics for product size recommendation in metric spaces.*

https://cseweb.ucsd.edu//~jmcauley/pdfs/recsys18e.pdf

Hsin-Yu Chen, Huang-Chin Yen, Tian Tian (2020). *Female Clothing E-commerce Review and Rating.*

https://github.com/hsinyuchen1017/Python-Prediction-of-Rating-using-Review-Text/blob/master/Female%20Clothing%20E-commerce%20Review%20and%20Rating.pdf
