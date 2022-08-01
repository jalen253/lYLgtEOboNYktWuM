# Happy-Customer
Customers Happy

Background:
We are one of the fastest growing startups in the logistics and delivery domain. We work with several partners and make on-demand delivery to our customers. During the COVID-19 pandemic, we are facing several different challenges and everyday we are trying to address these challenges.

We thrive on making our customers happy. As a growing startup, with a global expansion strategy we know that we need to make our customers happy and the only way to do that is to measure how happy each customer is. If we can predict what makes our customers happy or unhappy, we can then take necessary actions.

Getting feedback from customers is not easy either, but we do our best to get constant feedback from our customers. This is a crucial function to improve our operations across all levels.

We recently did a survey to a select customer cohort. You are presented with a subset of this data. We will be using the remaining data as a private test set.

Data Description:
Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers X1 = my order was delivered on time X2 = contents of my order was as I expected X3 = I ordered everything I wanted to order X4 = I paid a good price for my order X5 = I am satisfied with my courier X6 = the app makes ordering easy for me

Attributes X1 to X6 indicate the responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer.

Goal(s):¶
Predict if a customer is happy or not based on the answers they give to questions asked.

Conclusion
The best performing model is the Random Forest Classifier. The model predicts with a 81% accuracy/data accounted for and can properly account for a yes or no based on the target answer of "Y"

This model was decided upon by utilizing a Grid Search for the best hyper parameters and the feature selection was done based upon a CHI- Test which demonstrates which feature is the most useful towards calculating the Target Variable.

## Accuracy
.81