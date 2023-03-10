## Final Project for the Summer School 2022 on Data Science at the Barcelona School of Economics
This repository contains the notebook corresponding to the project. The task of the project was to use a data set of spanish tweets to illustrate the development of emotions around the events of
<a href="https://en.wikipedia.org/wiki/2017_Catalan_independence_referendum#:~:text=An%20independence%20referendum%20was%20held,by%20the%20Generalitat%20de%20Catalunya." target="_blank">October 01, 2017</a>.

This is achieved by finding meaningful emojis in tweets to label the tweets by their emotion. Since only a subset of the tweets contains such emojis, a machine learning model is trained on these labeled tweets and used to classify the remaining tweets by their emotional meaning.

The graph below shows the fraction of tweets associated with positive emotions over time.

![emotions](https://github.com/lstruth/tweets/blob/main/graph_fraction_positives.PNG)
