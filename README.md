# Neural_Network_Charity_Analysis
## Analysis Overview
The goal of this analysis is to create a neural network model that is able to predicting whether applicants will be successful if funded by Alphabet Soup. The dataset includes more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results
We use the following methods for the analysis:
- preprocessing the data for the neural network model,
- compile, train and evaluate the model,
- optimize the model.
Encoding of the categorical variables, spliting into training and testing datasets and standardization have been applied to the features.

### Compiling, Training, and Evaluating the Model
- This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.\
In the end, three hidden layers with 80, 60 and 30 nodes respectively are shown in the submitted model.
-Activations for the hidden layers were relu functions, with a sigmoid used in the output layer.
-Functionally, in working toward the model target of 75% accuracy, we added a hidden layer and increased neurons, but at a marginal gain over the initial challenge guidance. Removal of certain feature variables was also attempted, but with insufficient success to meet the model target.

## Summary
Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.The deep learning neural network model did not reach the target of 75% accuracy. We could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.
