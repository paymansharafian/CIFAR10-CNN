# CIFAR10-CNN
For cifar 10 data, we design a three-layer CNN network. Each layer includes a convolution, several filters and a maxpooling. Then we add two fully connected layers to it
Neural network specifications:
Conversion window size: three by three (3,3)
Stride size:
Is equal to for the convolution part.
For maxpooling is equal to 2. (2,2)
Number of filters per layer: In the first, second and third layers, we used 16, 32 and 64 filters, respectively.
Activator functions: Relu
Fully connected layer size:
We have two fully connected layers that have 512 and 10 neurons, respectively. In the last layer, the number of neurons should be 10 because the number of our labels is 10 and the data is finally classified into 10 categories.
Loss function: categorical crossentropy
Optimization method: adam
Mini-batch size: 100
