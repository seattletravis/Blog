# Travis Lamberte - Dev log is a blog!

## Date: 2/21/2024

## Title: AI machine Learning Model

For this project I propose building a Machine Learning model to do a simple function either linear, quardratic or sinusoidal.

Linear Function f(x) = mx + b
Quadratic Function f(x) = mx^2 + b
Sinusoidal Function f(x) = sin(x)

The AI model will simply take a value in and respond with the correct value that the function would provide, however the model will not be trained with the function, only input and output values provided from the function.

This simple AI will be enough to build an AI with all the best practice of AI Science.

AI characteristics:

Code Details: Python, Numpy, Pytorch, Pandas, Matplotlib, Jupyter Notebook, Anaconda (virtual env)

Deep Learning: input_layer, hidden_layer1, hidden_layer2, and output_layer

TYPE: Artificial Neural Network (ANN)

Number of Classes: 2, input and output

Activation Function: Rectified Linear Unit (ReLU) | y = wx + b where w = weight, b = bias

Optimizer: Adam - | optimizer = torch.optim.Adam(model.parameters(),lr=0.01) |

Epochs: 200 (1 epoch is 1 run through all the training data)
