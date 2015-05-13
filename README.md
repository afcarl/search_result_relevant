## Search Results Relevance

Kaggle competition on search result relevant, see more [here](https://www.kaggle.com/c/crowdflower-search-relevance/)


## Dependencies

- Scikit-learn
- Numpy
- Pandas
- BeautifulSoup
- unidecode


## Improvement

Improvement can be added in issue. We should submit carefully and report if we got beaten on Leaderboard.

- I haven't tried better classifiers and good cross validation technique
- We should check the preprocess texts if it all makes sense
- **Note** that `X`, `X_test` matrix is now from text without stemming (like remove s,es for plural for example)
- However, when we match to see if search result is in description, we use stemmed text
- We should add more vector columns to improve the result e.g. distance between search text and result text. We will have e.g. distance column but we should normailize it somehow.
- The 2 columns that I added is not linearly separable: 00, 01, 10, 11 we can think of column feature to make it separable 
- We will discuss more over the weekend


### Team Members

- Titipat Achakulvisut (Team Leader)
- Daniel Acuna
- Zaw Htet Aung
- Tulakan Ruangrong