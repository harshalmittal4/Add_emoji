# Add_emoji
This project aims at predicting the instinct of any input sentence and then associates an emoji to it accordingly.
Two models are being used here : numpy model and LSTM implemented in Keras.</br>

## Steps involved:
1) Words in each input sentence are first replaced with their corresponding indices and padding is done to make the length of each input the same.
2) Embedding layer is used which associates a 50 dimensional Glove vector representation to each index(each word) in the sentence.
3) LSTM model(graph) is built in keras.
4) Model is compiled and than trained on the training set.
5) Model is tested against the test set.
