# UFC-Predictions

This repository is my attempt at trying out different tools to predict the outcome of UFC fights.

Credit goes to mdabbert on Kaggle for consistantly updating this dataset of historical, previous and upcoming UFC events (https://www.kaggle.com/mdabbert/ultimate-ufc-dataset) as well as creating a template for preparing a prediction task submission.

My first attempt is to use Tensorflow Probability, splitting the data into a test set of 20% of all UFC fights in the historical dataset, using only the differential features (strike differential, takedown differential, etc.) to predict the winning probability of each fighter.
