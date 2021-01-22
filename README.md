# MNIST-digit-recognition-using-Keras-with-99.4%-accuracy

MNIST is most basic neural network that every Deep learning enthsiat must have a hands on.

**I tried this model and obtained a accuracy of 99.4%**

Being new to deep learning i leaned basics of neural networks, kernals, channels, layer functions & activation functions and then i tried MNIST_dataset which was already present under keras.dataset. The dataset contains 6000 images whose dimensions are 28x28x1. 

Looking at single channels, it was necessary to split it into more channels so to extract more features from all the digits and also increase the accuracy. Since loading the dataset is not a difficult, it is difficult to maintain the random_state, so if you ever run my code, it is quite a possibility that the results might differ(however running it few times will give u accuracy same as mine according to the central limit theory).

Using simple layers and maxpooling will yield an accuracy of 98% and thus i have used dense layer and dropout so to avoid overfitting.

For any queries on the notebook or understanding, contact this mail : pklappy21@gmail.com 
