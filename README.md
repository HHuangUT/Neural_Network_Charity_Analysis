# Neural_Network_Charity_Analysis

## Purpose

>With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

- Variable(s) that are considered the target(s) for your model?

    The IS_SUCCESSFUL column is the target.

- Variable(s) that are considered to be the features for your model

    Anything not removed/dropped is considered part of the model.

- What variable(s) are neither targets nor features were remove?

    Features 'EIN' & 'NAME' were dropped because both have little effect on the outcome

- How many neurons, layers, and activation functions did you select for your neural network model

    This model is made with an input features & four hidden layers. Each layer has 80,30,20, and 10 neurons respectively. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

- Was the model able to achieve the target model performance?

        Loss: 0.5530309081077576, Accuracy: 0.7279300093650818
    
    The model was not available to achieve .75

- What steps were taken to try and increase model performance?

    I increased the number of layers, the neurons within each layer, and changed activation types.


## Summary

The model accuracy ended up being around 73%, which did not meet the goal. 
To improve these numbers in the future I would:
    
- Drop more Features
- Gather more data