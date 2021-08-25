# Digit-Recognizer-Kaggle

This repository contains a trained shallow neural network for identifying gray-scale handwritten digits
The dataset for this code has been taken from [kaggle](https://www.kaggle.com/c/digit-recognizer)
The dataset consists of :
- 42000 training examples each containing a 28x28 i.e. 784 pixel values and the corresponding label(a digit between 0 to 9)
- 28000 testing examples each containing a 28x28 i.e. 784 pixel values and no corresponding label(The percentage match will be checked once you submit your code on kaggle)

I have trained a shallow neural network consisting of one layer of 10 neurons for doing this task submission .
I have tried to adjust the parameters and hyperparameters as much as possible and the best result amongst all trials turned out for a learning rate of 0.002 and training over 2000 iterations which yielded a training score of 76% and a test score of 71%.
