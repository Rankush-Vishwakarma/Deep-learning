# Deep-learning
In this repo I have tried to present different Deep learning algorithms with there implementation.

<h2>Neural Network</h2>
  - an independent calculation body can be called as neurons . The neural network is an algorithm that try to mimic the human brain. Neural network could be explain as the layer of single or multiple neurons combined together. 
  
Let's try to understand the neural network and neurons with the help of T-shirt Top seller Demand prediction example.
 
let say we have a single feature as price of T-shirt and we need to predict(Classify) if the T-shirt would be the top seller or not. 

Input = X = Price of T-shirt
let's say we are implementing logistic regression  for the classification purpose so our equation would be

![image](https://user-images.githubusercontent.com/96487589/188705659-b839c176-a784-4d1d-b006-f79c7804cf52.png)

here, F(x) is our predicting function this can be treat in the same way as Activation function (Activation function is used to measure how much a neuron is sending high output to other neuron down stream from it). 
This whole function F(x) is treated as the single neuron.

![image](https://user-images.githubusercontent.com/96487589/188706735-b99ab55c-1e42-4cb7-b252-a2a9731cd1cc.png)


This is very simple Example having one feature and only single neuron or activation function.


## Now let's try to understand how multiple neuron works, what is input layer?, what is hidden layer ? ,and what is output layer?.

Let's say we have two feature Price,shipping cost, marketing, and material now one way could be to minimize and extract some important thing from this feature like,
# important feature means the factors that could help in order to predict the probabolity of being a top-seller.
  ### Affordibity = Price + Shipping Cost
  ### Awareness  = Marketing
  ### Perceived quality = Material + Price
  
 ## these could be the minimized version or the feature that can contribute in predicting the probability. Now let's try to understand the same thing with the help of diagram.
 ![image](https://user-images.githubusercontent.com/96487589/188709981-56875b34-f0b2-44ae-8c65-7f1359f40572.png)

If we try to understand the diagram all the Factor here are getting calculated with the help of explicitly defining the criteria . But, in neural network for making the smooth and automatic extracting feature we will join all the feature each other , So in neural network we can do some thing like
![image](https://user-images.githubusercontent.com/96487589/188710943-766c5401-2fc3-4e51-8cc7-8e352c879ee1.png)
The Affordibility, Awareness , perceived Quality feature will get extract automatically with the help of neurons .
![image](https://user-images.githubusercontent.com/96487589/188712480-4b113d57-dc17-4c67-9ba5-cffdc58b7b1e.png)
