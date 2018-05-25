# How To Choose The Perfect Beer?

This is a perfect competition for persons who have a beginner’s level understanding of various concepts of machine learning and data science, and are looking to polish their understanding and check how they stand against a larger community.

Data scientists take their beer very seriously. Recommendations from friends? No thank you. Websites? Too many pop-ups. Ads? Yeah, as if. They can trust only true solid numbers. Here’s a fun fact: Last year, Indians drank a total of 4.7 million litres of beer and the number is expected to go up to 6.5 billion litres by 2022.

Newer brands are also entering the market — take Delhi-based startup Bira 91, for example. With the $50 million they have raised, Bira plans to flood India with more beer and fill in that gap between traditional inexpensive brands and expensive ones.

So how will data scientists choose their beer? Will they look at the combination of barley, water, hops and yeast arrived upon? There are many things to consider — a series of complex biochemical reactions need to take place to make the perfect beer.

That’s why, here at MachineHack, we have entrusted this very important job to the most trustworthy people in the world (especially when it comes to beer) to you, the data scientists.

#### Data:

The train and test data will consist of various features that describe a beer. In many beer cellars, important factors such as temperature and humidity are maintained by a climate control system. Hence features like Cellar Temperature and Serving Temperature become really important. This is an actual data set that is curated over months of primary and secondary research by our team. Each row contains fixed size object of features. There are nine features and each feature can be accessed by its name.

#### Features

*   ABV – Alcohol By Volume
*   Brewing Company
*   Food Pairing – Perfect food to have with this beer
*   Glassware Used – Perfect glassware to use to enjoy this beer
*   Beer Name – Name of the beer
*   Ratings
*   Score (Predict) – Overall score of the beer
*   Style Name – Style in which the beer is prepared
*   Cellar Temperature
*   Serving Temperature

#### Problem Statement

With the given nine features (categorical and continuous) build a model to predict the score of the beer.

#### Evaluation

**Goal**: It is your job to predict the score for each beer. For each beer in the test set, you must predict the score variable.

**Metric**: Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the predicted value and observed score values. The final score calculation is done in the following way:

1. X = Sigmoid of RMSE, which squashes the RMSE between the range of 0 and 1
2. Score = 1 – X, Hence, lesser the RMSE better your score is.

**Submission File Format**: Please do not change the format of the test file while submissions. Just fill up the price columns without touching any other data on the file.

