# Xg proof of concept


xG is the probability of a shot to be a goal given the position of the player and angle of the shot.

I have build a base model using XG-Boost to predict the probability of a shot will be a Goal.

Data: Statsbomb

Scrapped over 1000 matches in both genders(male and female) and proccessd the data to predict the probability of a shot is a goal.
Evaluation Metric:

This is an example of class imbalance data. We can either use precision or recall or both (F-Score)
