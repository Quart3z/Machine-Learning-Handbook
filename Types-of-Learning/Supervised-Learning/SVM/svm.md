## Support Vector Machine (SVM)
[< classification](../classification.md)
- find a hyperplane, that distinctly classifies the data points
- with optimal margin of the data points and hyperplane, and maximum distance between data points of classes with enough space and confidence for future additional data points
- support vectors, data points that are closer to the hyperplane, manipulate it to alter the position and size of hyperplane
- disadvantage: result is dichotomous as no probability of class membership is given
---

### Kernel Trick
- transformation of input dataset
- to classify non-linearly separable data and avoid overfitting
- methods: 
  - Gaussian/radial basis function (RBF)
    - general-purpose, when no prior knowledge about the data
  - Polynomial
    - popular in image processing
  - Sigmoid
    - proxy for neural network
