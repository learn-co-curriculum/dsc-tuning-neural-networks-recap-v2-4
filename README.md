
# Tuning Neural Networks - Recap

## Introduction

In this section, you built upon your previous understanding of Keras and neural networks in order to further tune these models to optimize performance. You saw how optimization can go wrong with exploding gradients if normalization is not properly applied and how to prune overfit models using regularization.

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

As a brief review, here are some key takeaways to remember going forward:

* In deep learning a training, validation and test set are used when iteratively building the right deep networks
* Like traditional machine learning models, we need to watch out for the bias variance trade-off when building deep learning models
* Several regularization techniques can help us limit overfitting: L1 Regularization, L2 Regularization, Dropout Regularization,...
* Deep network training can be sped up by using normalized inputs
* Normalized inputs can also help mitigate a common issue of vanishing or exploding gradients
* You learned about gradient descent, but in deep learning some other optimization algorithms are introduced that work faster than gradient descent
* Examples of alternatives for gradient descent are: RMSprop, Adam, Gradient Descent with Momentum
* Hyperparameter tuning is of crucial important when working with deep learning models, as setting the parameters right can lead to great model improvements

## Summary

Well done! You've now learned a lot about traditional, fully connected neural networks. From here, you'll begin to investigate alternative architectures that are useful for specific domains such as image recognition.
