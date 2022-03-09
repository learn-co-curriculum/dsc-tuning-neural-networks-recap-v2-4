# Tuning Neural Networks - Recap

## Key Takeaways

The key takeaways from this section include:

### Tuning Neural Networks

* Validation and test sets are used when iteratively building deep neural networks
* Like traditional machine learning models, we need to watch out for the bias variance trade-off when building deep learning models
* Examples of alternatives for gradient descent are: RMSprop, Adam, Gradient Descent with Momentum, etc.
* Hyperparameter tuning is of crucial importance when working with deep learning models, as setting the parameters right can lead to great improvements in model performance

### Regularization

* Several regularization techniques can help us limit overfitting: L1 Regularization, L2 Regularization, Dropout Regularization, etc.

### Normalization

* Training of deep neural networks can be sped up by using normalized inputs
* Normalized inputs can also help mitigate a common issue of vanishing or exploding gradients

### Convolutional Neural Networks

* CNNs are a useful model for image recognition due to their ability to recognize visual patterns at varying scales
* The essence of a CNN is a convolutional operation, where a window is slid across the image based on a stride size
* Padding can be used to prevent shrinkage and make sure pixels at the edge of an image receive the necessary attention
* Max pooling is typically used between convolutional layers to reduce the dimensionality
* After developing the convolutional and pooling layers to form a base, the end of the network architecture still connects back to a densely connected network to perform classification

