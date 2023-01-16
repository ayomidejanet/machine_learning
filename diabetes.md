# machine_learning

### MODEL CREATED TO PREDICT WHETHER A PERSON WILL/WILL NOT HAVE DIABETES.
I successfully created a model from a pre-existing data to predict whether a person is likely to get diabetes or not based on their blood pressure, insulin level, skin thickness, glucose level and pregnancy status.
The first thing I did was to replace the zeros in the data (as it is impossible for a living human to have a zero insulin/blood pressure in their body) with the mean values of what an average person should have based on the data.
I then split the dataset into a train and test data, scaled its features since I used a KNN algorithm that computes euclidean distance, defined the model, evaluated the model using confusion matrix and computed the f1 and accuracy score.
### Conclusion:
The model was created using KNN(euclidean metric and the accuracy which is 80% tells us that it is a pretty fair fit in the model.
