# Malaria_Cell_Detection
Kaggle Dataset Link: https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria

I implemented a convolutional neural network (CNN) for image classification using Keras. The model consists of three convolutional blocks.

In the first block, Conv2D layer with 32 filters, followed by batch normalization and ReLU activation, which helps to improve convergence speed and model performance. then applied max pooling to reduce the spatial dimensions.

The second and third blocks follow a similar structure, utilizing 64 and 128 filters. Each block also include batch normalization and ReLU activation, followed by max pooling . A dropout layer with a 40% dropout rate is added prevent overfitting.

After flattening the output, added two fully connected layers, both utilizing L2 regularization . Finally, the model concludes with a single output neuron using a sigmoid activation function, suitable for binary classification.
