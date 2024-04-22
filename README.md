# deep-learning-challenge

This challenge involves utilising some newly developed neural networking skills in order to develop a tool for a non-profit so that they can find low-risk funding applicants. The non-profit, named Alphabet Soup, possesses a CSV containing 34,000 organisations that Alphabet Soup has donated to previously.

## Preprocessing the Data

Preprocessing the CSV was done by using both Pandas and the "StandardScalar()" function of Scikit-Learn. This step is an important prerequisite before compiling, training and evaluating the neural network model. After loading in the dataframe, any unnecessary columns were removed. The number of unique values per column were ascertained, with those columns containing rare amounts of unique values being congregated into a new value called "Other". After encoding categorical variables, the data was split into a features and target array, represented by "x" and "y" respectively. Training and testing datasets were formed by using the "train_test_split" function. Finally, "StandardScalar()" was used to scale the training and testing features.

## Compile, Train and Evaluating the Model

TensorFlow was used to design a neural network/deep learning model to create a binary classification model to achieve the goal of this scenario. In addition to TensorFlow, Keras was also used to assign input features and nodes to create the neural network. Two hidden and one output layers with appropriate activation functions were added. The model was compiled and trained, and the results were examined for their loss and accuracy. The results were exported to an HDF5 file.

## Optimising the Model

Modifications to the model were made in an attempt to increase the predictive accuracy to beyond 75%. Three attempts were made but unfortunately the model was not able to reach the desired accuracy after making the changes to the models. These three attempts were captured in a separate Jupyter Notebook and HDF5 file with the word "Optimisation" added to the end of the file names.