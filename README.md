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



