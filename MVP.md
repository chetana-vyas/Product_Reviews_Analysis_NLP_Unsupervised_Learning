# MVP

## Product Reviews Analysis

## Data Description:

• [kaggle dataset] (https://www.kaggle.com/datafiniti/grammar-and-online-product-reviews)

• 71000+ reviews for 1000 products

### Features

* REVIEWS - concatenated reviewTitle + reviewText

### Target
* RATING - will be used later to build a Binary Classification, put the reviews into 2 buckets - Customers that are 'Happy' or 'Disappointed' with the product.

I have done text preprocessing using NLTK (Tokenization, Stemming), Topic Modelling. Here's the list of top 30 topics visualization using pyLDAvis library.

![topics](https://github.com/chetana-vyas/Unsupervised_Learning/blob/main/images/top-30-topics.PNG)

![Example-topic-2](https://github.com/chetana-vyas/Unsupervised_Learning/blob/main/images/topic-2-PersonalCare.PNG)
