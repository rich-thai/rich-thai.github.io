# Richard Thai Portfolio  

Hello! Welcome to my data analytics porfolio. I'm a physics PhD candidate seeking a career in the analytics industry where I can provide actionable insights for real-world business problems. My resume can be found [here](https://rich-thai.github.io/about-me). Feel free to contact me at richthai92@gmail.com!



### [Bike Share Toronto Project](https://github.com/rich-thai/BikeShareTO)
This is a project where I scraped real-time GBFS data from Toronto's Open Data library, and recorded the data in a SQLite database. GBFS is a standard for bikeshare information (similar to GTFS for transit data) and contains information such as the station capacity and bike availabilty. I studied the flow of bikes in and out of stations to study the traffic flow, and to see which stations are heavily used and under-utilized. See more details of this project at the link in the title.

### Bike Sharing Demand
[Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand/overview) was a Kaggle competition using a dataset provided by Capital Bikeshare. The bike rental data contains two years worth of information such as the date/time of the rental, weather, and seasonality. The task was to predict that demand of bike share rentals for selected hours of the days for multiple dates. I used a supervised machine learning model to predict the rentals, as shown in [this notebook](https://github.com/rich-thai/Bike-Sharing-Demand/blob/master/BikeSharing.ipynb).

### Restaurant Revenue Prediction
[Restaurant Revenue Prediction](https://www.kaggle.com/c/restaurant-revenue-prediction) was a Kaggle competition using a dataset provided by TFI, the company behind many fast food restaurants around the world. They provided the revenue, opening date, location, and obfuscated data for 137 restaurant locations, and the task was to predict the revenue for a list of restaurants. In this [notebook](https://github.com/rich-thai/Kaggle-Restaurant-Revenue-Prediction/blob/master/Restaurant.ipynb), I determined that a large fraction of the 37 obfuscated features are correlated and reduced the number of features by principal component analysis (PCA). I then performed a variety of supervised machine learning models to predict the revenue for the test set restaurants.
 
### Kobe Bryant Shot Selection
Every shot Kobe Bryant has taken was hosted on [this Kaggle competition](https://www.kaggle.com/c/kobe-bryant-shot-selection). My [notebook](https://github.com/rich-thai/Kobe-Shot-Distribution/blob/master/Kobe-Shot-Prediction.ipynb) explores the types of shots taken, ranks the success rate of each shot, and visualizes the shot distribution. For a set of shot IDs, the shot_made_flag values are removed and the task was to perform supervised machine learning to predict the probability that the shot was a success. 


### NLP Disaster Tweets
This is based on the Kaggle competition [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/overview). Trained a recurrent neural network to distinguish tweets that corresponded to real natural distasters and false ones. The note book can be found [here](https://github.com/rich-thai/Kaggle-NLP-Disaster-Tweets).
