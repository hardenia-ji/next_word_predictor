# next_word_predictor

In This next word prediction model , I used Long Short-Term Memory (LSTM) networks that provides the most appropriate next word from the previous sequence of words.I also build a Graphical User Interface using Tkinter where the user will get real time next word prediction while typing.We preprocess the text data, split it into training, validation, and test sets, and train the LSTM model on the training set. During training, the LSTM network’s weights are adjusted to minimize the difference between the predicted and actual next words.

Dataset :
The dataset used is the text form of the famous novel “Pride and Prejudice” written by Jane Austin.The dataset has a total of 733851 words and a vocabulary size of 7261 words. 

2.2. Data Preprocessing : 
In this step,we tokenized the text data into individual words, converting each word into a numerical representation, and splitting the data into training, validation, and test sets.Since LSTM network can only work with numerical data so each word is then converted into a numerical representation using techniques such as one-hot encoding or word embeddings.
