# Perfect_Olympic_Predictors

Project Overview:

Our project aims to use Python to analyze and predict Paris 2024 Olympic medal winners!

Using datasets from the Tokyo 2020 Olympic Games, we hypothesize that countries which have won medals in previous Olympics are more likely to win again in the future. Based on this hypothesis, we aim to predict the likelihood of each country winning a medal at the Paris 2024 Olympic Games. Our model considers various influencing factors, including the probability of a country winning any medal in the past and the percentage of winning teams sent from each country.

    A country's probability of winning in the past is calculated as the number of medals won by the country divided by the total number of medals possible to win (number of sporting disciplines multiplied by three (for gold, silver, and bronze medals)).

    The percentage of teams sent by a country that won is calculated by the number of medals won by the country divided by the number of teams the country sent to that Olympic game.

We utilize the Naive Bayes algorithm to train our machine learning model.

    P(A1 | B1, B2) = P(A1) * P(B1 | A1) * P(B2 | A1)

By leveraging Naive Bayes and historical Olympic data, this project provides a data-driven approach to predict Olympic outcomes, potentially aiding in strategic planning and preparation for future Olympic Games.

Using the Naive Bayes theorem above, we calculated the probability of a country winning a medal, given the proportion of times the country won a medal in previous Olympic games, the ratio of medals to the number of events they participated in, and the percent of "winning" teams that the country had.
We have summarized our findings below: 
![Probability_of_country_Winning_medal_bargraph](https://github.com/user-attachments/assets/6271c0df-1eba-4d64-b21d-45c20bdaf9f1)


From there, we utilized the dataset to build Naive Bayes learning models, capable of potentially predicting countries that will win medals in the future, given similar datasets. We built 4 models: Multinomial, Gaussian, Complement, and Bernoulli models to see which model would be trained the best in terms of accuracy and presicion. 

Here, we see how well our models predicted class 0 elements (countries that would not win a medal):
![Class 0 Comparison Graph](https://github.com/user-attachments/assets/7ade44d5-37f7-4a2d-82d8-c934ef02dc30)

How well our models predicted class 1 elements (countries that would win a medal):
![Class 1 Comparison Graph](https://github.com/user-attachments/assets/121836f4-1e8f-40fe-b8b1-d13ad6215603)

We see that all of our models had very high accuracy and precision, leading us to conclude that our models were trained well to predict whether or not a country would win a medal accurately and precisely. 

## Future adjustments/additions
We aim to continue this project to add specific predictions such as "how likely is a country to win a gold/silver/bronze medal" rather than simple win "a medal". 

We also hope to continue adding more and more datasets in order to continuously improve and adjust our training models so it could potentially be used as a reliable prediction model for future Olympic games. 


