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

## Testing and improving accuracy

<img width="868" alt="Screenshot 2021-11-01 at 7 33 40 PM" src="https://user-images.githubusercontent.com/93538009/139707056-93ccb316-e33a-482d-8291-f6cb8c13f511.png">
<img width="872" alt="Screenshot 2021-11-01 at 7 33 49 PM" src="https://user-images.githubusercontent.com/93538009/139707072-79ea64a9-2595-4cbb-b6a5-be684a0690a9.png">
<img width="872" alt="Screenshot 2021-11-01 at 7 33 57 PM" src="https://user-images.githubusercontent.com/93538009/139707076-0defd4c7-c040-4c68-8bdc-863822b61f4d.png">
