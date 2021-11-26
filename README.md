# Product Recommendation based on user reviews

Scrape user reviews from beeradvocate.com and recommend beer to a user based on their preferences. Compare the performance of different methods.

* [Scrapper](https://github.com/RahulSingla5209/sentiment_analysis/blob/main/scrapper.ipynb)- Major steps done:
  * Used BeautifulSoup for scrapping beeradvocate.com  
* [Recommendation Engine](https://github.com/RahulSingla5209/sentiment_analysis/blob/main/sentiment%20analysis.ipynb)- Major steps done:
  * Data Cleanup and User preference vector created
  * Calculate cosine similarity based on frequency of words in the user review
  * Sentiment scoring for each reviews - Sentiment Analyzer - VADER
  * Document similarity between user preference and user reviews - spaCy
  * Compare performance of different methodolgies used
