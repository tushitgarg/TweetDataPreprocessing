# TweetDataPreprocessing
![twitter icon](https://user-images.githubusercontent.com/40752274/63120789-a5ee6180-bfc0-11e9-987e-2c797af34e69.png)

### Cleaning the tweet text
Hey!<br>
Twitter is one of the largest sites with public opinions from all over the world which are open to getting access to.
Twitter is a gold mine of data and so is the best place for data if someone wants to do data analysis on public opinions.
To perform analysis on twitter data, some preprocessing and cleaning of tweet text is required.
<br>The jupyter notebook **twitter_tweet_preprocessing.ipynb** contains the python code to perform some data cleaning on the tweet text.<br>
### File containg some uncleaned tweets text.
**twitter_tweets_data.json** is an example file that contains some tweets with their tweet ids. The file is in json format.<br>
The task is to perform **data preprocessing** on these tweets.
### File containing the cleaned text.
**cleaned_tweets.text** file contains the output of the code after filtering the tweet text.<br>
Tasks performed were:<br>
- removing mentions.
- replacing consecutive non-ASCII characters with a space.
- removing stop words,emoticons,punctuations.
- removing extra whitespaces.
- removes urls
- removing newline character
- removing weired symbols

The cleaned tweets are now ready to be used for further data analysis ,applying Natural Language Propcessing techniques and machine learning techniques to get to amazing results.

## Main Python Libraries included in the code.
- Python NLP library **NLTK**<br>
Link to install and deploy the nltk library. (https://www.nltk.org/install.html)
- Python **regex** library. (https://pypi.org/project/regex/)
- Library to parse **json** objects.
