# Project Objective
### Part A:
We built a quartic function approximator using Tensorflow and Keras API to approximate how ReLU, tanh, and sigmoid activation functions behave using shuffled and unshuffled dataset using two different neural network structures.

#### Neural Network structures
*   Structure 1:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FCL: 12 Neurons (first hidden layer)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FCL: 8 Neurons (second hidden layer)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FCL: 4 Neurons (last hidden layer)
*   Structure 2:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FCL: 24 Nuurons (single hidden layer)<br>


#### Various cases
*   [Case 1](#case1):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: shuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 2](#case2):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: shuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 2<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 3](#case3):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: shuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: tanh<br>
*   [Case 4](#case4):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: shuffled and scaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 5](#case5):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: shuffled and scaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: tanh<br>
*   [Case 6](#case6):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: unshuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 7](#case7):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: unshuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 2<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 8](#case8):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: unshuffled and unscaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: tanh<br>
*   [Case 9](#case9):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: unshuffled and scaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: ReLU<br>
*   [Case 10](#case10):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data: unhuffled and scaled<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NN structure: Structutre 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activation function: tanh<br>

### Part B:
[A multilayer neural network has been built to approximate XOR encountered in digital logic.](#demo2)
