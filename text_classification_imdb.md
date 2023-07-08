## TEXT CLASSIFICATION
I used the IMDB dataset which contains the text of 50,000 movie reviews from the internet movie database. These are divided into 25,000 assessments for training and 25,000 assessments for testing. 
The training and test sets are balanced in a way that they contain an equal number of positive and negative reviews.
I first created a Keras layer that uses a TensorFlow Hub model to the embed sentences, and tried it out on some sample input
Then, built the model on the complete dataset. I then compiled the model using the loss function and adam optimizer.

Trained the model for 20 epochs in mini-sets of 512 samples. These are 20 iterations on all the samples of the tensors x_train and y_train. 
During training, I monitored model loss and accuracy on the 10,000 samples in the validation set.
Two values ​​were returned; loss: 0.336 and accuracy rate: 0.843
