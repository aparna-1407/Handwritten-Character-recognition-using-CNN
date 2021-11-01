# Handwritten-Character-recognition-using-CNN
This system recognises handwritten character input given as an image or drawn on the interface with 96.7% accuracy
This code uploaded is for handwritten digit recognition alone.

The CNN model has two convolution layers. 32 nodes/filters are used in the first layer and 64 nodes in the second layer. The activation function used is the ReLU, or Rectified Linear Activation. 

In the pooling layer MaxPool is used. Pooling window size is 2x2. 

A fully connected layer/dense layer is added with layer type ‘dense’. Again, the activation function used here is the ReLU, or Rectified Linear Activation.

In the ouput layer, the activation function used is ‘softmax’. 

After both maxpooling and fully connected layer, dropout is introduced 

The flatten is used on the feature maps before they are introduced to the fully connected layer. 

## Dataset used: http://yann.lecun.com/exdb/mnist/
