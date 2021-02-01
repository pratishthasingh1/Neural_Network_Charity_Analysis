# Neural Network Charity Analysis
## Overview of the analysis:
A charity data csv was used in an analysis that used machine learning and neural networks. The features of the datasets were used to make binary classifiers to predict if an organization will be successful if Alphabet Soup Foundation were to fund them. 
After preprocessing the data using density plots, data was trained with neural network. After adding several different layers and manipulating the nodes and activation functions, the reliability of the model was assessed. 
## Pre-process --> Compile, train and evaluate the model --> Optimize the model 

## Results:
Data Preprocessing
* What variable(s) are considered the target(s) for your model?  
    * IS_SUCCESSFUL column 
* What variable(s) are considered to be the features for your model?
    * All the columns excluding the target, "IS_SUCCESSFUL" column 
* What variable(s) are neither targets nor features, and should be removed from the input data?
    * "EIN" and "NAME" are neither targets nor features, therefore were removed. These columns do not impact the target. 

Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * For layers, I knew I wanted to use at least 3 layers. So to get the neurons, I took the original amount of features and multiplied it by 2 as I went up up each layer from layer 3. 
        * For instance layer 1 was 43 x 2 x 2
        * layer 2 was 43 * 2 
        * layer 3 was 43 
I used relu and swish for activation functions. According to articles online, it seems swish works well with relu and is almost even better than relu, according to some. 

* Were you able to achieve the target model performance?
    * No, but I am curious to see what would happen if we removed some more unnecessary data.

* What steps did you take to try and increase model performance?
    * I tried optimizing the model by removing noisy variables from features, adding more neurons and layers and using different activation functions. 

## Summary: 
I enjoyed working on this model as it allowed me to work more with neural network. I think we can improve the accuracy by removing unnecessary data and spend more time on preprocessing and transforming. 