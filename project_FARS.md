## Amazon Fake Review Machine Learning Classification

### Project Overview
For this project, we are given large datasets of product reviews, which contain details such as the review title, review text body, star rating, how many people voted “helpful,” and the time the review was posted.
**Verified** = product was bought on Amazon 
**Unverified** = product not bought on Amazon but might be bought from 3rd party seller

We sought to answer the question:
How well can we predict whether a review comes from a verified purchase or not?

### Dataset Description
The team used US Amazon Customer Reviews datasets from Amazon archives. The reviews were taken over the span of the years 2014 - 2015.

The collection of reviews is organized into sub datasets for each product category. The collection contained datasets for 46 different product categories, and each dataset contains 15 features for each review. 

### Analysis
#### KNN Classification
- Assigned weights to parameters or the contributions of each data point referencing a review.
- Used weights so that nearer neighbors contribute more than distant ones (weight based on distance formula) 
- Applied VADER sentiment analysis to compute the polarity scores (sentiment) for the reviews
- Cons: “majority voting” when class distribution is skewed so need to weight classification

#### Random Forest Classification + Bigrams
- Cleaned review body (remove stop words, html tags, punctuations, numbers; lowercase + lemmatize) 
- Converted review into list of bigrams (each pair of words)
- Engineered features to quantify “fakeness”
- Random forest classifier: each node of tree considers a certain number of features → prediction made by averaging over the predictions of each tree
- **Pros:** the ONLY input required is the review body. Does not need star rating or number of helpful votes.
- **Cons:** low accuracy + cannot predict well for one-word reviews

EXAMPLE UNVERIFIED REVIEW:

<img src="images/User Input Analysis Result in Jupyter Notebook 1.png?raw=true"/>

What the Features Mean:

<img src="images/What the Features Mean.png?raw=true"/>

### Jupyter Notebook Demo

<img src="images/Jupyter Notebook Demo.gif?raw=true"/>

### Steamlit Demo

<img src="images/Streamlit Demo.gif?raw=true"/>

### Results

[Final Poster Presentation]([https://www.chulavistaca.gov/departments/development-services/permitdata](https://docs.google.com/presentation/d/1KT1pRrMsNNqqwLilf-bxJz7jnnCtfJ1ba6sJtZwbf6I/edit?usp=sharing))

<img src="/Final Poster.png?raw=true"/>
