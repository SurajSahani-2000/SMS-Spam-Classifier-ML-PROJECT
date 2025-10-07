# SMS-Spam-Classifier-ML-PROJECT
My First SMS Spam Classifier Project
Hi there! This is my first machine learning project where I'm building a system to figure out if a text message is spam or not. It's a fun way to learn about how computers can understand and work with text.

What this project does
The main goal is to create a simple model that can look at an SMS message and tell if it's a spam message (like an advertisement or a scam) or a normal message (called "ham").

How I built it
Here are the main steps I followed in this project:

Getting the Data: I started by loading a dataset of SMS messages that were already labeled as either spam or ham.
Cleaning the Data: Raw data can be messy! I cleaned it up by removing extra columns that weren't needed, handling any missing information, and getting rid of duplicate messages. I also changed the labels (spam/ham) into numbers so the computer can understand them.
Adding Features: I created some new pieces of information from each message, like how many characters, words, and sentences it has. These help the model learn patterns.
Looking at the Data: I did some basic checks to see how the spam and ham messages differ based on these new features.
Splitting the Data: I split the data into two parts: one for the computer to learn from (training data) and one to test how well it learned (testing data).
Training a Model: I used a simple machine learning model called Naive Bayes and trained it using the training data and the features I created.
Checking the Model: Finally, I tested the model on the testing data to see how accurate it was at predicting spam or ham messages.
What I used
I used Python and some helpful libraries like:

pandas for working with the data in tables.
nltk for some text-related tasks (like counting sentences).
scikit-learn for the machine learning model and splitting the data.
matplotlib and seaborn for creating charts and visualizations.
Next Steps (Ideas for the future)
Maybe try different ways to represent the text, like looking at which words appear most often.
Try training other types of simple models to see if they perform better.
Look at other ways to measure how good the model is, not just accuracy.
This project is a work in progress and a learning experience!
