# next_word_predictor

In This next word prediction model , I used Long Short-Term Memory (LSTM) networks that provides the most appropriate next word from the previous sequence of words.I also build a Graphical User Interface using Tkinter where the user will get real time next word prediction while typing.We preprocess the text data, split it into training, validation, and test sets, and train the LSTM model on the training set. During training, the LSTM network’s weights are adjusted to minimize the difference between the predicted and actual next words.

Dataset :
The dataset used is the text form of the famous novel “Pride and Prejudice” written by Jane Austin.The dataset has a total of 733851 words and a vocabulary size of 7261 words. 

2.2. Data Preprocessing : 
In this step,we tokenized the text data into individual words, converting each word into a numerical representation, and splitting the data into training, validation, and test sets.Since LSTM network can only work with numerical data so each word is then converted into a numerical representation using techniques such as one-hot encoding or word embeddings.

2.3. LSTM Model Architecture Design : 
This involves determining the number of LSTM layers(2), the number of hidden units per layer(1000), the learning rate(0.001), and other hyper-parameters. 

2.4. Training the Model : 
Once the LSTM model architecture has been defined, the model is trained on the training set using the sequence of words as input and the next word as output. During training, the weights of the LSTM network are adjusted to minimize the difference between the predicted and actual next words. The training process involves several epochs(70), where the entire dataset is fed to the model multiple times to refine the model’s parameters.

2.5. GUI Design :
After the training, the GUI is build for the user to interact with the model with the help of Tkinter module in Python. The GUI enables the user to get real time next word suggesstions while typing. The User can type words on the empty text area and word predictions are provided on the right side similtaneously.

<img width="371" alt="Screenshot 2023-11-30 040848" src="https://github.com/hardenia-ji/next_word_predictor/assets/114081218/28438527-cc78-4cbe-9238-8e38389ed27f">
