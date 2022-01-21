## Deep Learning
- works well with big data
- automatic feature extraction
- able to learn non-linear relationship of dataset

Inspired by biological structure of brain, an interconnected group of nodes, called neural network was used in the machine learning process.


https://ijai.iaescore.com/index.php/IJAI/article/view/7539/0

https://tvst.arvojournals.org/article.aspx?articleid=2762344

### Parameters Initialization
- configuration of the weights and bias
- weight:
    - Weight is the parameter that transforms input data within hidden layers
    - decide the importance of the feature on predicting the result
- bias:
    - allows adjustments to the output, shifting the activation function to right or left
    - shift the activation function to positive or negative

### Forward Propagation
- each of the neuron includes an activation function, weights and bias
- generate an output based on the inputs received and its activation function

### Loss Evaluation
- minimizing the cost function to find a set of parameters which represent the data
- cost function measures "how good" a neural network did with respect to its given training sample and the expected output

### Backward Propagation
- adjust the weights and biases for better result on next iteration
- optimal value is found through gradient descent