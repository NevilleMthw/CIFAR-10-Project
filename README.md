# Computer Vision/Deep Learning Project

The project deals with the use of deep learning technologies to classify images of different day-to-day objects/beings. The project is created using the Python programming language with additional libraries such as Tensorflow, Keras, and Numpy.

The dataset used is a variation of the CIFAR-10 dataset. The images are of different objects/beings and are classified into 8 categories. The categories are: airplane, automobile, bird, cat, deer, dog, frog and horse. The default image size in this dataset is 32x32 pixels of RGB values.

The following image is the ML pipeline used in the project:
<br>
<img src='ML Pipeline Design/ML Pipeline Design.png' alt='ML Pipeline Design'>
<br>

The project structure is as follows:
<br>
1. Data Ingestion
2. Data Preprocessing
3. Model Learning
4. Model Evaluation
5. Model Prediction

Data Ingestion: Importing the required libraries and dataset.
<br>
Data Preprocessing: The dataset is preprocessed to be used in the model. The techniques of preprocessing the dataset are:
<br>    
    1. Grayscale Conversion
    2. Normalization
    3. Guassian Blurring
    4. Image Rotation
<br>
Model Learning: The model is trained using the preprocessed data. The model implemented is a convolutional neural network (CNN).
<br>
Model Evaluation: The model is evaluated using the test data. The evaluation metrics used are:
<br>
    1. Accuracy
    2. Monitoring the loss
<br>
Model Prediction: The model is used to predict the category of the image on the test data. No new images are used for prediction.
<br>

References:
<br>
1. https://www.section.io/engineering-education/image-preprocessing-in-python/
2. https://iq.opengenus.org/basics-of-machine-learning-image-classification-techniques/
3. https://www.analyticsvidhya.com/blog/2020/02/learn-image-classification-cnn-convolutional-neural-networks-3-datasets/
4. https://medium.com/@dipti.rohan.pawar/improving-performance-of-convolutional-neural-network-2ecfe0207de7
5. https://github.com/y33-j3T/Coursera-Deep-Learning/blob/master/Advanced%20Computer%20Vision%20with%20TensorFlow/Week%201%20-%20Introduction%20to%20Computer%20Vision/Copy%20of%20C3_W1_Lab_2_Transfer_Learning_CIFAR_10.ipynb
6. https://victorzhou.com/blog/keras-cnn-tutorial/


