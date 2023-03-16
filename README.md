# 700745488--Assignment-6-Ashwin-kumar-Reddy

Here is the video link stating the explanation
https://drive.google.com/file/d/1wYigEVDFluAaCPFkUsU17-DQcJmump8f/view?usp=sharing

In class programming:
1. Use the use case in the class:
    a. Add more Dense layers to the existing code and check how the accuracy changes.
2. Change the data source to Breast Cancer dataset * available in the source code folder and make required
changes. Report accuracy of the model.
3. Normalize the data before feeding the data to the model and check how the normalization change your
accuracy (code given below).
from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
Breast Cancer dataset is designated to predict if a patient has Malignant (M) or Benign = B cancer

A) In this program first we are importing keras because Keras allows you to choose which lower-level library it runs on, but provides a unified API for each such backend, then we are importing sequential which is used to create models layer by layer and then importing dense and activation because Dense Layer is used to classify image based on output from convolutional layers. Each Layer in the Neural Network contains neurons, which compute the weighted average of its input and this weighted average is passed through a non-linear function, called as an “activation function”. Additionally we are implementing pandas and numpy libraries  and the reading diabetes.csv file and data is trained and tested and then finally finding the accuracy and prinitng it and along with we are adding more dense layers to the existing code and finding the accuracy of it and next we are changing the data set to breast cancer  and then importing libraries like pandas,train_test_split,LabelEncoder,Sequential,Dense and then loading the breast cancer data set and extracting the features and labels and printing it, Apart from this we are encoding the labels and splitting data into training and testing sets and then defining the model architecture, finallly we are training the model and then evaluating the model on the test data and priniting the accuracy, next we are normalizing the data before feeding to the model and we are loading breast cancer data set from csv file and then extracting the features and labelsof it and encoding the categorical labels further we are scaling the input features and then defining neural network model for breast cancer detection and finally prinitng the accuracy on test set


 2) Use Image Classification on the hand written digits data set (mnist)

1. Plot the loss and accuracy for both training data and validation data using the history object in the source
2. Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model
on that single image.
3. We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the
activation to tanh or sigmoid and see what happens.
4. Run the same code without scaling the images and check the performance?
​A) First we are processing the data  and then we are converting data to float and scale values between 0 and 1 and then convert each image of shape 28*28 to 784 dimensional which will be fed to the network as a single feature and next convert data to float and scale values between 0 and 1, Additionally, we are changing the labels frominteger to one-hot encoding to_categorical is doing the same thing as LabelEncoder() and next creating a network, then  Plotting the loss and accuracy for both training data and validation data using the history object in the source code, next plotting one of the images in the test data, and then do inferencing to check what is the prediction of the model on that single image.Apart from this we change the number of hidden layer and the activation to tanh or sigmoid and see what happens and then printing accuracy of that and running the same code without scaling images and checking performance.
