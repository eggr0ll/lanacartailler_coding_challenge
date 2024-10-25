## VDS Application Level 3
#### Objective Section Responses
1. What evaluation metrics did you choose to use?
   1. I used loss, accuracy, precision, recall, and binary cross entropy. 
2. What was the score you got for each of these metrics?
   1. Accuracy: 0.7289
   2. Precision: 0.2142
   3. Recall: 0.7939 
   4. Binary_crossentropy: 0.5135
3. Mention any resources you used to help you in this portion of the challenge (we love links!).
   1. I used the [Keras website](https://keras.io/api/metrics/) for the neural network metrics.
4. Any extra information you'd like to include.
   1. Precision is a useful evaluation metric for this focus question because it suggests that there are false positives outputted by the model. However, it might be better to have false positives than false negatives, as false negatives would likely lead to untreated heart disease. 
   2. In real world terms, the accuracy evaluation metric represents the proportion of known diagnosed heart disease responses that the model accurately predicted.