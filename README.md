# George-Detection-with-Convolutional-Neural-Networks-CNN-
George Detection with Convolutional Neural Networks (CNN)


This project implements a binary image classification model using a Convolutional Neural Network (CNN) to detect whether an image contains George or not.The dataset consists of image URLs,with images of George and non-George labeled accordingly.These images are fetched via URLs and processed using techniques like resizing,normalization,and data shuffling to prepare them for model training.



1)KEY FEATURES:-

Data Preprocessing : The dataset consists of images loaded from URLs and preprocessed (resized and normalized) for model training.

CNN Architecture : The model deploys a multi-layer CNN with convolutional,max-pooling,and dense layers,utilizing relu activation and dropout for regularization.

Training and Validation : The model is trained using binary_crossentropy loss and adam optimizer for binary classification,achieving impressive results on validation data.

Image Prediction : The model can predict if "George" is present in any test image provided by the user.



2)TOOLS & LIBRARIES:

TensorFlow/Keras for building and training the CNN.

OpenCV for image processing.

Pandas for managing the dataset.

Requests for handling image data from URLs.


3)RESULT:

Achieved a test accuracy of over 80% in detecting Georg.(because,here i split the dataset into a  new one,contain less url than the orginal to make the prediction more speedly,you can use this same code for orginal dataset)

Generates classification reports for evaluating the model's performance.
