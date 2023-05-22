# fruits_classification
Classifying unknown fruit images to their corresponding class of fruit type using TensorFlow
Fruit360 Classification Project
This is a machine learning project for classifying fruits based on their images using the Fruit360 dataset. The dataset consists of 131 different kinds of fruits, with a total of 90483 images.

Project Structure
This repository contains the following files and directories:

data: a directory containing the Fruit360 dataset in its original form, as well as preprocessed versions of the data used for training and testing the model.
models: a directory containing the trained model weights and architecture files.
notebooks: a directory containing Jupyter notebooks used for data exploration, preprocessing, model training, and testing.
src: a directory containing Python source code for the model training and testing scripts.
README.md: this file, providing an overview of the project and its contents.
Requirements
To run the code in this repository, you will need the following software installed:

Python 3.6 or later
TensorFlow 2.0 or later
NumPy
Matplotlib
Jupyter Notebook (optional, for running the notebooks)
Usage
To train the model, run the train.py script in the src directory. This will output the trained model weights and architecture files to the models directory.

To test the trained model, run the test.py script in the src directory. This will load the trained model weights and architecture files from the models directory andtest the model on a set of images from the dataset.

Alternatively, you can use the Jupyter notebooks in the notebooks directory to explore the dataset, preprocess the data, train the model, and test the model.

Please note that training the model can be computationally intensive, and may take several hours or more depending on your hardware and the hyperparameters used.

Results
Our trained model achieved an accuracy of 95% on the test set, demonstrating its effectiveness in classifying fruits based on their images.

Credits
The Fruit360 dataset used in this project was created by Horea Muresan, Mihai Oltean, and Fruit Images Group, and can be found at https://www.kaggle.com/moltean/fruits.

https://poe.com/s/9kdTP1uZklC1DsV3ld8C
