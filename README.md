# Spam_Filter_with_Naive-Bayers
## PROJECT DESCRIPTION
In this project, we're going to build a spam filter for SMS messages using the multinomial Naive Bayes algorithm. Our goal is to write a program that classifies new messages with an accuracy greater than 80% — so we expect that more than 80% of the new messages will be classified correctly as spam or ham (non-spam).

The purpose of the project is to classify  a dataset od messages as their spam or non-spam, to accurately classify the message the following has to be achieved;

To classify messages as spam or non-spam:

1. Learns how humans classify messages.

2. Uses that human knowledge to estimate probabilities for new messages — probabilities for spam and non-spam.

3. Classifies a new message based on these probability values — if the probability for spam is greater, then it classifies the message as spam. Otherwise, it classifies it as non-spam (if the two probability values are equal, then we may need a human to classify the message).

So our first task is to "teach" the computer how to classify messages. To do that, we'll use the multinomial Naive Bayes algorithm along with a dataset of 5,572 SMS messages that are already classified by humans.

The dataset was put together by Tiago A. Almeida and José María Gómez Hidalgo, and it can be downloaded from the The UCI Machine Learning Repository. 


Note that due to the nature of spam messages, the dataset contains content that may be offensive to some users.