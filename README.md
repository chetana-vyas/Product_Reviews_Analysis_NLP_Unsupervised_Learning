# Product Reviews Analysis

## Goal:
To understand the following about Product Reviews - what are most frequently used words, distribution of the length of the reviews, understanding fake reviews, spelling errors, predicting product rating using the reviews, etc. 

## Data Description:

• [kaggle dataset] (https://www.kaggle.com/datafiniti/grammar-and-online-product-reviews)

• 71000+ reviews for 1000 products

### Features

* id
* reviewsText
* reviewTitle
* reviewRating
* purchasedProduct
* recommendProduct
* brand	/ manufacturer
* categories
* pack_size
* descriptions
* dateAdded

### WORKFLOW

* EDA (data cleaning) 
* NLP (tokenization, removing stop words, stemming)
* TOPIC MODELING (NMF with TF-IDF Vectorizer)
* RECOMMENDATION SYSTEM (content based filtering using the terms from reviews using cosine similarity matrix)
* CLASSIFICATION SYSTEM (Logostic Regression and Decision Tree Classifier)

![topics](https://github.com/chetana-vyas/Unsupervised_Learning/blob/main/images/Topic_Interpretations.PNG)

Recommendation System example - 

Input - 'skin cream'

Recommendations: 
* 'Olay Total Effects Daily Moisturizer
* '7-In-1 Anti-Aging, 0.5oz'
* 'Olay Regenerist Deep Hydration Regenerating Cream'
* "L'oreal Paris Revitalift Triple Power Deep-Acting Moisturizer"
* 'CeraVe SA Renewing Cream'
* 'Shea Moisture African Black Soap Problem Skin Facial Mask'
* 'Tree Hut Shea Body Butters, Coconut Lime, 7 oz'
* 'Nivea Extended Moisture Body Lotion

I have done Dimensionality Reduction using PCA, and also tried K-Means clustering.
