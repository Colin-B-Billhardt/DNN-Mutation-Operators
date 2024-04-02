# DNN-Mutation-Operators
Research novel mutation operators that can be used to build new mutation testing tools for deep learning systems.

MNISTDecisionTree is novel code that is based of the following research papers [Property Inference for Deep Neural Networks](https://arxiv.org/abs/1904.13215) and [NNrepair](https://arxiv.org/abs/2103.12535)

MNISTModel file follows a tutorial presented on Kaggle. [kaggle-MNIST-tutorial](https://www.kaggle.com/code/prashant111/mnist-deep-neural-network-with-keras#MNIST---Deep-Neural-Network-with-Keras)



mnistDecisionTree:


Split into different code blocks, each executing or visualizing a single task. 


layer_outputs funtion:
-gets the dense layer outputs for the selected layer
-make sure to switch the file path of the saved model in this function to your own
-acts_combined will be the array of output values

tranfrom_to_activation_values function: 
-takes the acts_combined array values and switches them to on/off (1 or 0). If the value is > 0 then it becomes 1 and if it is < 0 then it becomes 0. 
-act_array is now the new array with the updated on/off values.

is_data_correctly_classified function:
-goes through the data points and checks if they have been correctly classified or not (this is useful for the decision tree building/vizualization)
-make sure to change the file path of the saved model in this function to your own


The next code blocks are the building of the decision tree followed by the vizulization of the decision tree and the accuracy of said decision tree. 


The next code block extracts all decision tree paths and (currectly) outputs them to console. Following this, the next code block outputs all incorrect decision tree paths. 

The final code block is my attempt to implement contraint solving.


mnistModel: 

This is the code used to train and save the model that is used in the mnistDecisionTree code. 
-Make sure to change the file paths to your own relevant file paths.





