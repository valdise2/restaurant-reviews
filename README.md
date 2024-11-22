# restaurant-reviews
This project involved wrangling data and applying NLP workloads using Python. The goal of the project was to preprocess data, highlight key insights, and to determine a list of features that would be suitable for machine learning models.

*Key insights*

A sentiment analysis of reviews for the restaurant shows that 50% of customers had a positive experience,
while the other 50% had a negative experience. Out of 1,000 reviews, 500 customers "Liked" the restuarant, and
another 500 did not. A word cloud was generated from the positive reviews. Customers that left positive reviews placed an emphasis on
the quality of food and service, with many of them feeling that these items were "good" and "great".

A word cloud was also generated from the negative reviews. These customers most commonly mentioned "food", "place",
"service", and "time". We can infer that these customers did not have a favorable opinion of the restaurant as a
whole, likely due to long wait times or poor food/service quality. 

*Features for modeling*

I plan to use review length (body_len) and punctuation percentage (punct%) as features
for modeling. These features, which were previously skewed, now have normal distributions
after undergoing power transformations. The normally distributed data is cleaner and will 
allow models to understand the data better without overfitting. These features will lead to more accurate
predictions for machine learning models. 

Dominic Valdiserri / MGT 661
