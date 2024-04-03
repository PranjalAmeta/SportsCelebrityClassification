<h3>Sports Celebrity Classification Model<h3>

<h2>Overview<h2>

This repository contains a deep learning model for classifying images of sports celebrities using convolutional neural networks (CNNs). The model is trained to recognize famous sports personalities such as Virat kohli,Max Verstappen,Lewis Hamilton,Niraj Chopra,Rafael Nadal,Lionel Messi.

<h2>Dataset<h2>

The model is trained on a custom dataset consisting of thousands of labeled images of sports celebrities. The dataset includes images collected from various social media platforms and official websites of sports leagues and teams

<h2>Model Architecture<h2>

This model consists of Haar Cascades Algorithm in which Cascade function is used to detect the face and two eyes of the celebrity folowed by convolution neural network which is well
suited for image classification.It consists of various convolution layer followed by max pooling for feature extraction.The extracted features are then flattened and passed through
the fully connected layer.As it is Multi-class classification the final layer uses Softmax Activation Function to produce probabilities for each class.

<h2>Evaluation<h2>

The performance of the model is evaluated using the tensorflows accuracy,precision and recall.
Additionally confusion matrices are generated to visualize the models performance across different classes.
