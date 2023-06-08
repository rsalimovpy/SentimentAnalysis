# SentimentAnalysis
Sentiment Analysis of Billboard HOT 100
The goal of our project was to analyze the lyrics gathered from the Billboard Hot 100 song chart and determine whether or not that song would end up having a negative, neutral, or positive sentiment. Our data set contained lyrics from Billboard Hot 100 songs ranging from the year 2000 until 2022. Since our data set was given to us from one of our previous group mates, I will include the csv files that we used when submitting the final project so you can load them from whichever local machine you are using.

Some interesting and surpring results are as follows:

    Songs with a positive sentiment are more likely to end up on the Billboard Hot 100 as opposed to negative songs.
    Songs that portray stronger sentiments are more likely to appear as opposed to weak sentiments on the Billboard Hot 100

Our predictions are below:

    Predict if a song will be positive, neutral, or negative based on their lyrics.
    Create a scale that shows how negative or positive a song is.

Our inferences are below:

    Achieve a way of differentiating positive and negative songs.
    Be able to predict what makes a song negative or positive.

Our conclusion was that we were able to use the NLTK package to assign sentiment to song lyrics, which determined whether they were positive, negative or neutral. We were then able to perform Logistic Regression on our model to predict with a 0.79 accuracy what makes up a positive song, which are specific words in the song themselves. The weight of the words then determined how positive or negative that song would be.
