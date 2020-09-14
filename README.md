# Sentiment-in-vegan-related-tweets

This is the final project of Andreas Opedal and me for the course Social Data Science offered at ETH Zurich in the spring semester of 2020. 

In this project, we investigated whether there is a correlation between the additiude of the population of a country, measured by the sentiment of the tweets including on of the hastags "vegan", "plantbased" or "dairyfree', and several country statistics. These statistics we investigated are GDP/capita, HDI, GII, CCPI and FOI. 

In this repo, we provide the code for extracting the country of the tweet, based on the geo-tag of the tweet, the code in which we performed the data analysis and our final paper. 

Note that in the code in which we extract the country from the geo-tag of the tweet, we use the Library GeoNames. For a non-professional account, GeoNames has a rate limit of a bit over 1000 tweets per hour, and for larger datasets the code thus needs to be run in batches. 
