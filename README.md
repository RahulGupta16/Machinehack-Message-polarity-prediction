# Message Polarity Prediction : Weekend Hackathon #3

![wk3-banner_2-1536x864](https://user-images.githubusercontent.com/56091634/83671648-a9f07c00-a5f2-11ea-9603-9c1abfe6cac0.jpg)


All of us receive a ton of messages and emails on a daily basis. Collectively, that is a lot of data which can provide useful insights about the messages that each of us gets. What if you could know whether a certain message has brought you good news or bad news before opening the actual message. In this challenge, we will use Machine Learning to achieve this.
Given are 53 distinguishing factors that can help in understanding the polarity(Good or Bad) of a message,  your objective as a data scientist is to build a Machine Learning model that can predict whether a text message has brought you good news or bad news.
You are provided with the normalized frequencies of 50 words/emojis (Freq_Of_Word_1 to Freq_Of_Word_50) along with 3 engineered features listed below:
TotalEmojiCharacters: Total number of individual emoji characters normalized. (eg.  )
LengthOFFirstParagraph: The total length of the first paragraph in words normalized
StylizedLetters: Total number of letters or characters with a styling element normalized
Target Variable: IsGoodNews

## Data Description

The unzipped folder will have the following files.
Train.csv – 947 observations.
Test.csv – 527 observations.
Sample Submission – Sample format for the submission.

## Evaluation
The leaderboard is evaluated using F1 Score for the participant’s submission.

## Rank : 43

## Online score : 0.9508197

## Local score : 0.9595745799083806
