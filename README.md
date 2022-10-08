### Analysis of the tweets posted on @weratedogs on Twitter.
The analysis involves 3 main parts which are:
1. Data Collection.
2. Data Wrangling.
3. Data Visualization.

#### Data collection
1. A csv file contains information about a particular tweet with features as tweet id, dog name, dog state, timestamp, rating numerator, rating denominator etc downloaded locally and saved as twitter-archive-enhanced.
2. A tsv dataset obtained programmatically with the module: requests and saved locally into a file named images-tweets.tsv. It contains information about the predictions of a neural network algorithm created to predict images of dogs in a picture. It has features such as first prediction, second prediction, third prediction etc.
3. tweet_json.txt was obtained by querying Twitter API with Tweepy. Each line in the txt file holds the attributes of each tweet id, retweets and favorite counts precisely and was saved as json.

#### Data Wrangling
This part handled the cleaning, transforming and merging of the dataset which was saved as twitter_archive_master. Also, exploratory analysis of the datasets to derive insights from the datasets.

#### Data visualization
This section holds the visualization of the meaningful insights derived from the analysis.

All the steps of the analysis was done with python libraries: pandas, numpy, matplotlib, seaborn, wordcloud, re, json and tweepy.
The consumer key, consumer secret, access key and access secret were imported from the module <code>keys</code>
