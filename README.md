# Asst4-Classic_MNIST
It was observed that if we increase the no.of neurons in the hidden layer to be more than that in the input layer, the model gives better training and test accuracy.
If we increase the no.of neurons to around 1200-1400, the training accuracy is a bit lower than that for 900 but the test accuracy is higher. Which means increasing the no. of neurons in hidden layer makes the model better. Greater the no.of neurons, better the representation of data. Increasing the no. of neurons to an extremely huge level will not make much difference, just reduce accuracy by a small bit.
Epochs should be around 5. Making it 10 increased the training accuracy but reduced the test accuracy thus making the model overfitted.
Decreasing the no.of neurons in the layers, decreases accuracy as the input layer itself has 784 neurons and thus a small amount of neurons wont be able to represent such huge amount of data properly.
Increasing the layers doesnt have that much effect on the model as the no. of neurons. If all layers have same no. of neurons, it doesnt make much difference. Otherwise, its better if first hidden layer has larger no.of neurons (as input has more neurons) and the last hidden layer has smaller no.of neurons( as output has only 10 neurons).
For activation function, the combination of Relu and Softmax is best. They give better accuracy than sigmoid and tanh.
For optimizer, Adam is much better than SGD and MSE as loss gives a bad accuracy.

Did not quite understand on what basis to choose optimizer and loss function.
