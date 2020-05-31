# Udacity-Deep-Learning
This repository contains all the projects completed as part of the Udacity Deep Learning Nanodegree Program. There are 4 projects uploaded in this repository which makes use of different neural networks such as CNNs, RNNs, and GANs. The different architectures are explored and implemented using various datasets. 

The first project is a Dog Breed classifier implemented using Convolutional Neural Networks. It works on 2 datasets which contain Dog and Human images, identifies whether a Dog or a Human is present in the given image and outputs the corressponding Dog breed for the identified dog image. 2 different architectures have been trained, a model from scratch and a model using transfer learning.

The second project is a Fake TV Script generation project implemented using RNNs and LSTMs. It works on the 'Seinfield TV script' dataset, used to train the RNN model. It then generates a fake tv-script based on the learning, which may not be completely correct.

The third project makes use of Generative Adversarial Networks (GANs) to generate human faces. It is trained using the 'CelebA' dataset which contains images of various celebrities, however, the dataset is not balanced as it contains images of mostly white celebrities. A GAN architecture is trained and used to save the generated samples in a file. The images generated are low-resolutioned, therefore, the model can be tuned to generate better resolution images.

The fourth project deploys a Sentiment Analysis model using a simple web-app. It has been trained on the popular IMDB dataset to detect whether a given movie review is positive or negative. The model makes use of a simple RNN architecture, trained using the AWS Sagemaker service. The trained model is deployed using AWS Sagemaker, AWS Lambda and AWS API Gateway.
