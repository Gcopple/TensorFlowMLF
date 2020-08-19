# TensorFlowMLF
Tensor Flow Google Video Series 

## Day 1: Learning the basic syntax
Do's and Don'ts:
Use np.array and specify dtype float

model is my object and I used tf.keras.Sequential karas is an ml framework and sequential means that I will have a sequence of layers in my neural network
[keras.layers.Dense(units=1, input_shape=[1])] is my layer it is a Dense which is the simplist layer we have one nuron in this layer and the input shape will tell us the shape of the layer we will train our value on.

model.compile(optimizer='sgd', loss='mean_squared_error') the optimizer is stocastic gradient decent and the loss is how we calcuate loss, so we will find the mean square error and report it each epoch

model.fit( var, result, epochs = nubmer of iterations)
don't forget to print model.result to see my answer and feed [numb]
COMMENTS:
I need to understand the optimzer better and the loss better. I'd like to know more about adding neurons, about loss, and about layers. 


## Day 2: Learning about Computer Vision
Computer Vision uses pictures, who knew!

We use images that are already classified to train our neural network and then we will use a new data set or subset to test our model. 
So, Don't use items that are in the training set to test the network!

use numbers for our item names not strings.

Flatten will take our nxn array and transform it into into a 1xm array
.relu: If the output of a neuron is less than zero it will set it to zero.
.softmax: This will take the highest value and set it to one and all other values to zero. This is used on classificaiton problems as we do not often want a likelyhood we would like a classification.

NOTE: when building a neural network all input data has to be the same size. AND we will have as many output neurons as we have classifications, so 10 classifications will mean 10 output neurons.

You can stop epochs early by making statements like in ex2 logs.get() >percent

COMMENTS: I need a greater undstanding of classes and their inputs.
