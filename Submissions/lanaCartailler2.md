## VDS Application Level 2
#### Objective Section Responses
1. What is your plan for creating this model? (you don't have to go into too much detail, just a general idea of what you are going to do)
   1. After cleaning the data, I will calculate class weights to address the imbalanced data. Then, custom weights for the features will be defined. The model architecture will be defined as well through the addition of layers.
2. Describe the algorithm that you chose and include why you think it is best suited for your problem.
   1. I chose a sequential neural network, which works by moving information from an input layer through hidden layers to a final output layer. There are neurons in each layer that connect to one another and have associated weights, helping the model learn the relationships in the data. I chose to use this model because it is well-suited for complex and non-linear relationships, which describes the relationships between the recorded clinical factors and the presence of heart disease.
3. Mention any resources you used to help you in this portion of the challenge (we love links!).
   1. I mostly used GeeksforGeeks ([like this article](https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/)) and Google's Machine Learning website ([like this article](https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data)). I also used the [Keras website](https://keras.io/guides/sequential_model/) for the neural network.
4. Any extra information you'd like to include.
   1. N/A

