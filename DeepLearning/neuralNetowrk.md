## Neural Network
### Feed forward (FF)
- non-cyclic full connections between nodes
- linear separability
- single-layer perceptron network:
- multi-layer perceptron networ:
- radial basis network (RBF):
    - only have 1 hidden layer
- algorithm:
    - parameters initialization
    - for n < epoch:
        - forward propagation
        - loss calculation
        - backward propagation
- not suitable for image processing. due to the large amount of fully connected layers. May cause overfitting.
---

### Convolutional Neural Network (CNN)
- able to capture spatial and temporal dependencies of an image
- better fitting to the image dataset due to reduction in number of parameters involved and reusability of weights
- consists of:
    - input layer
        - image size consists of the dimensions and channel(s)
grayscale image with 1 channel, RGB image with 3 channels

    - feature extraction layer
        - compute a dot product between a small region in the input volume and the weights they are locally connected to
        - convolutional layer
        - ReLU layer
        - pooling layer
    - classification layer
---

