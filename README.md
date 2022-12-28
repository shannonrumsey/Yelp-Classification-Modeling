# Yelp-Classification-Modeling


### Goal:
I aimed to determine whether the city of a business could be classified or predicted based on review data. To do this, I collected a large dataset of reviews for businesses in different cities and used machine learning techniques to build and compare the performance of four different models.



### Codebook:
Name / Data Type / Description

name / character / Name of the food-related business

city / nominal / Carpenteria, Goleta, Isla Vista, Montecito, Santa Barbara, and Summerland. City that the food-related business is in

latitude / double / Business's location with respect to the equator

longitude / double / Business's location with respect to the meridian

business_rating / ordinal / 1.5, 2, 2.5, 3, 3.5, 4, 4.5, and 5. Overall rating a business receives from Yelp users

review_count / integer / Number of reviews left on the page of a particular business

bad_count / integer / Total number of occurrences of the word "bad" in the reviews left on a particular business

good_count / integer / Total number of occurrences of the word "good" in the reviews left on a particular business

sentiment_score / double / The ratio of positive words in all reviews for a business divided by the total number of words

mean_len / double / The average length of reviews left on the business page

review_stars / double / The average number of stars left on the business by users who wrote a review

useful_stars / double / Total number of instances a review was voted "useful" on the busienss's page

funny_total / double / Total number of instances a review was voted "funny" on the busienss's page

cool_total / double / Total number of instances a review was voted "cool" on the busienss's page
