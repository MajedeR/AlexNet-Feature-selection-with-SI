# AlexNet-Feature-selection-with-SI

In a convolutional neural network, by passing the input data through the filters, we reach a new space where some of the obtained features may not have useful information to separate the classes from each other in the classification process. In this case, you can use the methods that exist to reduce the dimension and select the effective features. In this project, the aim is to use the SI complexity index for feature selection and dimensionality reduction in the AlexNet model.

In AlexNet_model.ipynb, we build the AlexNET model by adding pooling layers after each convolution layer (to reduce the number of features) and train the model with 1220 data from the MNIST dataset (which is separated from the original MNIST dataset in a balanced way) and save the model
