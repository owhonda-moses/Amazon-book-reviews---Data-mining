# AMAZON BOOK REVIEWS
## INTRODUCTION

> In this project, we delved into a comprehensive analysis of Amazon book reviews utilizing various analytical techniques in R. Our exploration aimed to extract meaningful insights into reader sentiments, preferences, and trends hidden within the reviews. Through text mining, sentiment analysis, topic modeling, and exploratory data analysis, we uncovered valuable findings that shed light on the dynamics of the reviews. Our dataset contained 17,939 books which have a total of 59,296 reviews.

### TEXT MINING

By means of tokenization, the review text was broken down into smaller units, including words and bigrams to extract meaningful insights from the reviews. Text preprocessing tasks including removal of stop word and lemmatization was performed to further aid the  extraction of content-related words from the reviews.

### SENTIMENT ANALYSIS
The Bing and AFINN sentiment lexicons were used to analyze and quantify the sentiments or emotional tone expressed in each review. The scoring systems of both lexicons was then analyzed to analyze their performance.

### TOPIC MODELLING
The Latent Dirichlet Allocation (LDA) topic model was used to discover latent thematic structures within the review text. This involved selecting specific book genres, creating a term-document matrix, text preprocessing, term selection, and analyzing the coherence, perplexity, and log-likelihood metrics to obtain the optimal number of topics for the model. The topics from the model were analyzed for topic coherence and similarity.

### EXPLORATORY DATA ANALYSIS
Several exploratory data techniques were carried out on the features. Some of which include, investigating if the number of reviews influence the price of a book, if the length of reviews determined how helpful users found the reviews, if review sentiments correlated with average ratings of books, most popular book, etc.


### KEY FINDINGS
From the text mining, we identified prominent themes such as “book,” “read,” and related terms, indicating a strong focus on literature and reading habits among reviewers.
In the sentiment analysis, we found a prevalence of positive sentiments across reviews. However, variations existed between the two lexicons, suggesting nuanced interpretations of sentiment.
With the LDA topic model, we identified eight distinct topics, ranging from fictional narratives to culinary delights, providing insights into the diverse content covered in the reviews.
In the EDA, while “Fiction” emerged as the most reviewed genre, deeper analysis revealed variations in reader preferences across genres. Also, while a correlation between ratings and sentiment scores was observed, the relationship was not definitive. Higher ratings did not consistently correspond to higher sentiment scores, indicating the multifaceted nature of reader perceptions and preferences.
The most reviewed book is Eldest (Inheritance, Book 2) by Christopher Paolini however, based on ratings and number of reviews, the best selling book is Charles Dickens’ Great Expectations. We also found that the price of the books were not influenced by the number of reviews, and more users found the reviews more helpful than not.


#### PACKAGES USED:

- R Studio
- LDAvis


_Notable references for this project include -_
- https://stackoverflow.com/
- https://github.com/
- https://www.geeksforgeeks.org/


_Note: The dataset used is a modified version of the Amazon reviews dataset available on Kaggle._