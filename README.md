# CIFAR-10-Object-Recognition

The project involves training a model on a dataset comprising 50,000 labeled images. 
Each image is 32x32 pixels in resolution and is in color. 
The dataset is categorized into 10 distinct classes, with each class containing 6,000 images. 
The primary goal is to employ the ResNet50 architecture, a convolutional neural network model, to train and classify the images into their respective classes.

Key Steps:

1. Dataset Import: The dataset is imported using an API token generated from Kaggle, accompanied by a JSON file, and the files are extracted.
2. Library Import: Essential libraries, including TensorFlow and Keras, are imported for the project. Data preprocessing steps are implemented.
3. Train-Test Split: The dataset is split into training and testing sets, with a test size of 0.2.
4. Data Scaling: To ensure uniformity, the data is scaled.
5. Neural Network Model Construction: A neural network model is constructed using Keras layers.
   The model is compiled with specific optimizers, loss functions, and metrics.
6. Model Training: The model is trained using the training dataset.
7. Utilization of ResNet-50: ResNet-50, a convolutional neural network model, is employed for object detection. The model achieves a sparse categorical accuracy of 0.6327.
8. Prediction: The trained model is used to predict outcomes on new data.
