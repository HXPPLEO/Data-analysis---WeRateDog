# Data-analysis---WeRateDog
A project from Udacity, cleaning and analysing the tweet archive of Twitter user @dog_rates,also known as WeRateDogs.
(i)
Data files used for analysing, provided by Udacity,
1. twitter_archive_enhanced.csv: The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

2. image_predictions.tsv: The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

3. tweet_json.txt: Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. 


(ii)
The file 'project#' consist of following files,
1. act_report.pdf(in Chinese)： communicates the insights and displays the visualizations produced from my wrangled data.

2. wrangle_report.pdf((in Chinese)): to briefly describes the process of wrangling. 

3. wrangle_act_#：my Python codes for wrangling, written on jupyter notebook

4. 数据可视化i_#: data visualization1，2，3........

5.twitter_archive_master：cleaned dataset.
the suffix # is a number indicates the version, largest means lastest
