# Data-analysis---WeRateDog
A project from Udacity - Wrangle and Analyze Data 

Three files that contain the data for analysing, provided by Udacity,
1. twitter_archive_enhanced.csv: The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

2.image_predictions.tsv: The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

3. tweet_json.txt: Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. 
