# About the Project
This is a midterm project for the course CISB62 in Mt.SAC.
## Description
This project is aimed to classify handwritten math symbols based on the dataset on Kaggle. The contributor of the dataset created a new one similar to MNIST but with higher resolution and also added other math symbols such as +, -, and x, y, z.

You can find the dataset here: <br>**Handwritten Math Symbols** https://www.kaggle.com/datasets/sagyamthapa/handwritten-math-symbols

With this dataset, I used different deep learning techniques to build two different models. The main steps are as follows:

- Split data into different folders and load data using tf.data.Dataset API.
- Analyze and preprocess the data to prepare for the training.
- Use AlexNet Architecture and Keras Tuner to build a model by tuning learning rate and activation function.
- Use pre-trained model (VGGNet19) to build another model to see which one performs better.
- Use the better model to evaluate the performance with confusion matrix and classification report.
- Save the final model and test it with my own handwritten images.

Please check [here](CISB62_midterm_project_Chao.ipynb) to see my project in detail.

##
