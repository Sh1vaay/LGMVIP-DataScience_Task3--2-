# Next_word_prediction
First, gather a large dataset of text to train my model on.
Next, Preprocess the data to get it ready for training. This involves tokenizing the text into individual words and encoding them as integers. 
Once data is prepped and ready to go, use Keras to build my model.Use an RNN with LSTM cells because they're really good at remembering long-term dependencies in the data. And also add an embedding layer to help my model learn meaningful representations of the words.
After building model, train it for as more no.epochs as possible using the training data. During training, keep track of the accuracy and loss so that you can see how well your model is doing.
Once training is complete, use matplotlib to plot the accuracy and loss over each epoch. This helps to see how well  model is learning and identify any issues that might need fixing
test it on test data.
