# NYC Taxi Fare Predictions
### Tomoya Tokunaga (mailto: ttokunag@ucsd.edu)

This repository contains my self-project about estimating New York City taxia fare amounts using the data from Kaggle(source link is [here](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)). I started off this project with cleaning the datasets with Pandas, and then observed relations of each data category to find a good cue for good estimation. I used visualizations with matplotlib to explain what factor put great influence on fare amounts. I finalized this project producing fare amount estimation with the linear regression algorithm. The following picture depicts one of the hardest parts of this project. I had a hard time in the data-cleaning process to get rid of invalid points floating on the ocean.

<img src="https://github.com/ttokunag/machine_learning/blob/master/NYU_taxi_fare_predictions/map_sample.png" width="1050">

*If the notebook cannot be loaded or loaded slowly, the following is the HTML version of the notebook.
http://ttoku.com/nyc_taxi_fare_pred.html

### Explanation on files
**NYC_taxi_fare_pred.ipynb**<br>
This is the jupyter notebook file I implemented machine learning model to make predictions

**sample_submission.csv**<br>
Files for the fare amount data. Since the data size is so huge, I do not use entire data for my analysis

**test.csv**
A data file to check the machine learning model performance
