Learning pytorch from https://www.youtube.com/watch?v=V_xro1bcAuA

what is deep learning?
Machine learning is turning things (data) in to numbers and finding patterns in those numbers.

Typical flow:
Input >>> Numberical encodings  >>>    Feed to neural network   >>>   Representation outputs >>>>> Human readable outputs
(images,                                          (identify patterns/features/weights)
documents,
audio)

What is a neural network?
3B1B: https://www.youtube.com/watch?v=aircAruvnKk

Convolutional neural network: good for image recognition
Long short-term memory network: good for speech recognition

Plain vanilla NN => multilayer perceptron -> even in this simplest form it can learn to recognize digits.

Perceptron: artificial neuron - oldies
sigmoid neuron : more modern neurons but they are considered old now

What are these weights? To specify the importance of a given input. This gets adjusted automatically throughout when the backpropagation happens.

Learn more: download the code that does this:


What are the neurons? A thing that holds a number, a number between 0 (black) and 1(white). The grayscale value of the corresponding pixel. This number inside the neuron is called its "Activation".

First layer of the network: All the neurons in the network. For ex, in a 28x28 pixel network, there are 784 neurons with activation in them.

Last layer in the network: Repesents how much the system thinks the given image. The higher the activation the more the system thinks it is the number. Now, we shall look at the two intermediate layers, they are called the HIDDEN layers.

The activations in one layer bring about the activations in the other layers.

The left most layer has pixels, second layer has the edges, third layer has the patterns and the final layer has the actual number made from the patterns.

PIXELS ===> EDGES ====> PATTERNS ====> Final number recognition

In audio, we pick out sounds to form syllables, which can be combined together to form words, which combined to form phrases and more abstract thoughts.

At the end, each neuron is a function (earlier, we called it a thing that holds a number). In essence the whole NN is one complicated function that takes in 784 numbers and spits out 10 numbers.

Sigmoid function --> To squiss the activation values between 0 and 1. Later it has been replaced by ReLU function as it is faster than sigmoid.

What's a tensor?
https://www.youtube.com/watch?v=f5liqUk0ZTw



Books to read:
**************
neuralnetworksanddeeplearning.com

Useful sites:
learnpytorch.io
zerotomastery.io

Informational sites:
paperswithcode.com