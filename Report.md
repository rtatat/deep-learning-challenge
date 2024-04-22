# Alphabet Soup Charity Report

*Data Preprocessing*
1. What variable(s) are the target(s) for your model?
    
    The "IS_SUCCESSFUL" column from application_df

2. What variable(s) are the features for your model?

    Every other column was the features of the model, which was done by dropping the target column from the dataframe.

3. What variable(s) should be removed from the input data because they are neither targets nor features?

    Both the "EIN" and "NAME" columns were removed from the dataframe as they added nothing to the analysis.

*Compiling, Training, and Evaluating the Model*
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

    My first attempt used 9 hidden nodes in the first layer and 19 in the second. This was to make an initial evaluation of the accuracy of the model, which could be adjusted later.

2. Were you able to achieve the target model performance?

    I was not.

3. What steps did you take in your attempts to increase model performance?

    I adjusted the number of hidden nodes in both layers in the second attempt and in the third i increased the number of epochs from 100 to 200 while maintaining the number of nodes from the second attempt

*Summary*

Overall, the model could only obtain an accuracy of about 72.6% across the different attempts. To increase this accuracy rating, a model that could draw a greater correlation between input and output would, in all likelihood, increase the overall prediction accuracy. This could be done by removing additional columns from the dataframe that may not be relevant to the overall analysis or by tinkering with the layer and epoch options until a higher accuracy rating was obtained.
