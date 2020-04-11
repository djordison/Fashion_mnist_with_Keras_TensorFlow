# Fashion_mnist_with_Keras_TensorFlow

### Following tutorial: 
https://www.tensorflow.org/tutorials/keras/classification

Basic prediction engine using 3 layer sequential model. 
* flatten 28x28 to 748x1 
* dense layer ReLU activation to 128x1
* dense layer to 10 nodes
* optimized on 'Adam', losses = crossentropy, metric = accuracy

Update 4/11:
Added SVC with linear and quadratic. Noted lower algorithm times on linear with lower accuracy.

Also of interest in the SVC application that only one selection is made wheras in neural net probabilities of each attribute exist.
