# Sentiment-in-vegan-related-tweets

This is the final project of Andreas Opedal and me for the course Social Data Science offered at ETH Zurich in the spring semester of 2020. 

In this project, we investigated whether there is an association (in terms of empirical correlation) between the attitude towards vegan diets, proxied by the sentiment of vegan-related tweets, and country level indices like GDP/capita, Human Development Index, Global Innovation Index, Climate Change Performance Index and Future Orientation Index.

We provide the code for extracting the Twitter data, a sample file for data pre-processing, country extraction using geotags as well as the sentiment and correlation analyses. Data extraction, pre-processing and analysis were performed in R. Country extraction was made using the geo-tags that come with the tweet data, and this part was done with the library GeoNames in a Python notebook.
Note that in the code in which we extract the country from the geo-tag of the tweet, we use the Library GeoNames. For a non-professional account, GeoNames has a rate limit of a bit over 1000 tweets per hour, and for larger datasets the code thus needs to be run in batches. 

The project paper is also published in this repo.

R libraries: dplyr, rtweet, sentimentSetsR, syuzhet, tools, WDI

Python libraries: geopy, nltk, numpy, pandas, unicodedata
