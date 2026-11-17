# sms-spam-classifier

Standard model for guessing if the message in an email is spam or not spam.
The baseline by guessing that it's all good is 87% so we gotta beat that.

The goal is to create a matrix with rows being the messages in a training set of emails and the columns being the amount of times the word appears in the message.
Based on the word counts and the label of the message (spam or not spam) we can compare the probabilities of a word appearing in a spam message.
Naive Bayes is useful for that (not perfect but its alright, quick and effective).

The model predicts with an accuracy of 98%.
I have to note though, that the model lets through more false negatives than false positives. 

The project is subject to change in the future.


*************************
The data set used is an old SMS Spam Collection.
