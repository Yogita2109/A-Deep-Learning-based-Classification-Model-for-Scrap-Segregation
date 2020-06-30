# A-Deep-Learning-based-Classification-Model-for-Scrap-Segregation
The data set used for this project is available on:
https://www.kaggle.com/techsash/waste-classification-data

Waste management is a pervading issue and is increasing day by day with the surge in urbanization. So, it is necessary to manage the waste for the development of ecological sustainability. One of the elementary approaches is to segregate the waste at the initial stage in order to dispose the waste accurately. Moreover, it requires enormous effort, manpower and time to sort the scrap manually. Image processing and deep learning approaches used to classify the scrap can be effective and beneficial. The the objective is to segregate the garbage into organic and recyclable wastes using Convolutional Neural Networks(CNN). 

DATASET:
The dataset comprises 25077 images of organic and recyclable objects. It is divided into train data (85%) and test data (15%). Training data contains 22564 images and the test data contains 2513 images. 

DATA PREPROCESSING:
The dataset can be preprocessed using the Keras library. Keras provides the ImageDataGenerator class that defines the configuration for image data preparation and augmentation. It creates augmented image data which reduces your memory overhead but adds some additional time cost during model training. Further, this preprocessed data is used to fit in the proposed model.

METHODOLOGIES:
A deep-learning method, Convolutional, Neural, Networks (CNN) which is based on Tensorflow and Keras has been used to create a model capable of classifying images of different waste objects.

RESULT AND CONCLUSION:
Convolutional Neural Networks(CNN) is one of the efficient approaches used for image classification, as it automatically detects the important features of the image as we go deeper into the layer without any human supervision. It is computationally efficient . It uses special convolution and pooling operations and performs parameter sharing which  enables CNN models to run on any device, making them universally attractive. It is a cost effective approach that it can be implemented by simply using the camera. The major advantage is that it avoids overfitting efficiently. Our model successfully classifies the images into organic and recyclable wastes. The model achieved an accuracy of 91.25% on the validation set.





