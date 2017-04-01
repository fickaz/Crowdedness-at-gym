# Crowdedness-at-gym
Data exploration, statistical estimation, bayesian stats.

This open dataset is obtained from Kaggle.com. Below is the description copied from the website. Credit goes to the uploader.

Background

When is my university campus gym least crowded, so I know when to work out? We measured how many people were in this gym once every 10 minutes over the last year. We want to be able to predict how crowded the gym will be in the future.

Data

The dataset consists of 26,000 people counts (about every 10 minutes) over the last year. In addition, I gathered extra info including weather and semester-specific information that might affect how crowded it is. The label is the number of people, which I'd like to predict given some subset of the features.

Label:

Number of people
Features:

timestamp (int; number of seconds since beginning of day)
day_of_week (int; 0 - 6)
is_weekend (int; 0 or 1)
is_holiday (int; 0 or 1)
apparent_temperature (float; degrees fahrenheit)
temperature (float; degrees fahrenheit)
is_start_of_semester (int; 0 or 1)
