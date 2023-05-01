# Nerual Nets
## Deep Neural Networks and TensorFlow

### Deep Neural Networks

Deep Neural Networks (DNNs) are a type of Artificial Neural Network with multiple layers between the input and output layers. These systems are designed to model the way the human brain works in order to 'learn' from large amounts of data. While a DNN with a single layer can still make approximate predictions, additional hidden layers can help optimize accuracy.

![Deep Neural Network](https://www.researchgate.net/profile/Tharindu-Rukshan-Bandaragoda/publication/323164864/figure/fig1/AS:601657315921930@1520356245769/An-example-of-a-deep-neural-network-with-two-hidden-layers-Each-circle-represents-a.png)

### TensorFlow: An Open Source Machine Learning Framework

TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.


TensorFlow provides multiple APIs. The lowest level API--TensorFlow Core-- provides you with complete programming control. The higher level APIs are built on top of TensorFlow Core. These higher level APIs are typically easier to learn and use than TensorFlow Core. In addition, the higher level APIs make repetitive tasks easier and more consistent between different users.

![TensorFlow API Layers](https://ekababisong.org/assets/seminar_IEEE/tensorflow_api.png)

 We create a model with a single dense layer. The model is compiled with a stochastic gradient descent (SGD) optimizer with a learning rate of 0.1 and mean squared error (MSE) as the loss function. Finally, the model is trained on our training data.


## Data Resource
Fashion MNIST Dataset (https://keras.io/api/datasets/fashion_mnist/) is loaded from keras.dataset. It consists of 70000 28 \times 28 grayscale images of 10 fashion categories, 60000 of which are typically used as labeled training examples, where the other 10000 are used for testing your learning model on. 
