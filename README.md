# Car-Price-Prediction

# Algorithms
The classification script is written in Python, making use of the Jupyter Notebook to display graphs. I used scikit-learn’s classification functions.

I used a random forest classifier with roughly 500 to 1000 estimators, aka the number of trees in the forest. The number of features to consider for the best split is the square root of the number of features, which is the automatic setting.

# Results

# Popularity

Popularity was scraped and put into JSON file, so it was a trivial matter to load this into Python and plot a bar graph. The top ten most popular cars are as follows, from most to least: Ford, BMW, Audi, Ferrari, Honda, Toyota, Nissan, Dodge, Kia, and Porsche.

# Important Features

The most important features in determining the price of cars are found to be the engine horsepower, the engine fuel type, and the engine cylinder, which is sensical since they determine how well a car runs. Model types, the make, and the year come after; these have more to do with the brand and superficial appeal of the car, but are still deciding factors nonetheless.

# Most Overpriced Cars and Brands

I hoped to do a more in-depth analysis of car prices and the effects of branding. I have seen that a car’s make and model type may affect its price quite significantly. In order to determine is a car is overpriced or not, wI ran the classifier without these features. The most overpriced cars are found to be the ones with the greatest difference between its projected price (by the algorithm) and its actual price (the testing values). In addition to individual models, I took a look at the most overpriced brands.

The results do not disappoint; indeed it seems that the most overpriced brands are those that sell ridiculously priced cars that everyone wants to buy but don’t have the money for it (also the cars that come up the most in mainstream music).
