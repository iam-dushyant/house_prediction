# Introduction
The housing prices have been obtained from Pararius.nl as a snapshot in August 2021. The original data provided features such as price, floor area and the number of rooms. The data has been further enhanced by utilising the Mapbox API to obtain the coordinates of each listing.

# Steps of implementation
1. Assessing the data
I start by first assessing the size of data and the type of parameters available for analysis.
2. Splitting train and test data
I want to use supervised learning to assess and predict house prices. But also, how do I start with the split? So, I will be using an iterative approach of splitting from the range of 50% to 80%, with increments of 5% in each iteration, to see what my ideal split is. This would be reviewed when the learning is done and the accuracy is obtained.
3. Supervised learning
This is where I use ML models to predict house prices, but then again, where do I start from?
4. Accuracy
I am using Confusion Matrix to assess accuracy.