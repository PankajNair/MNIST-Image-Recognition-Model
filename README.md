# MNIST-Image-Recognition-Model
## Problem Statement
MNIST image recognition is a well-known problem in the field of machine learning and computer vision, where the goal is to correctly classify handwritten digits from 0 to 9. Although many deep learning-based models have achieved high accuracy rates on this dataset, there are still challenges in accurately recognizing digits in real-world scenarios. One of the key challenges is the presence of noise, blurring, or distortion in the images, which can significantly affect the performance of the recognition model. Furthermore, the problem is compounded when the dataset is imbalanced, with unequal representation of the different classes. The development of an accurate and robust MNIST image recognition model is essential for various real-world applications such as automated postal address recognition, signature verification, and optical character recognition (OCR). The primary goal of this project is to develop a deep learning-based model that can accurately classify MNIST images with high accuracy, even in the presence of noise and distortion, and can handle imbalanced datasets to improve the robustness of the recognition system.
## Data Information
The dataset for the model is the default dataset available in the keras library. There are two MNIST test images each with varying noise and distortions.
## Project Pipeline
* Understanding the Data:  We load the data and check the size of the dataset.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As this is the default dataset in keras, the data is already balanced and processed. We standardize each data value by dividing it by 255.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. As we are using the default keras dataset, the train and test data can be directly unpacked.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use keras and Tensorflow to build the model. The model has 5 layers, the input and hidden layers having relu activation and the output layer having softmax activation. We also need to evaluate the models using appropriate evaluation metrics.
