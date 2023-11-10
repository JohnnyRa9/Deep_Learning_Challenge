Overview

The goal of this project was to predict the likelihood of applicants achieving success if they receive funding from Alphabet Soup. I will be using machine learning methods to train and assess the model's performance. The objective is to attain an accuracy score greater than 75%.

Results

Data Preprocessing

What variable(s) are the target(s) for your model?
    The IS_SUCCESSFUL column in the dataset which is the target variable of the model.

What variable(s) are the features for your model?
    The feature variables are every column other than the target variable and the non-relevant variables such as EIN and names.

What variable(s) should be removed from the input data because they are neither targets nor features?
    The non-relevant variables that aren't targets or features will be dropped from the dataset that might potentially confuse the model.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
    I included 3 layers: 1: An input layer with 80 neurons, 2: A second layer with 30 neurons, and 3: An output layer with 1 neuron. I chose this so that the total number of neurons are more than double.

Were you able to achieve the target model performance?
    Out of the 100 epochs I was able to achieve an accuracy score of about 74% for the training data.

What steps did you take in your attempts to increase model performance?
    I tried adding 2 dropout layers and changed the activation function to tanh. The optimization was increased by .1% for the training data.

Optimization attempts

The final optimization accuracy score was 73%. After two attempts to optimize my model, I did not achieve a goal of 75% accuracy score.

Summary

Ultimately I was not able to attain the target accuracy of 75%, if I had more time I would have attempted to use a different classifier to attempt to reach the given goal.