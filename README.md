# Add_emoji
Two models are being used : numpy model and Keras model.</br>
The LSTM model (in keras) predicts the instinct of any input sentence and associates an emoji to it accordingly.

## Steps involved:
1) Words in each input sentence replaced with their corresponding indices and padding done to make length of each input the same.
2) Embedding layer associates a 50 dimensional Glove vector representation to each index(each word) in the sentence.
3) LSTM model(graph) is built in keras.
4) Model is compiled and than trained on the training set.
5) Model tested against the test set.
