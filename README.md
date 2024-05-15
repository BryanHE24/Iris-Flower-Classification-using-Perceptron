# Iris Flower Classification using Perceptron

This Python script demonstrates how to use a perceptron model to classify iris flowers based on their petal length and width. 
The iris dataset is a popular dataset in machine learning, often used for classification tasks.

## Summary of what the code does
The program implements a machine learning workflow to classify iris flower species using a Perceptron model based on their petal measurements. 
Here are the key steps it performed:
  1) Imported Necessary Libraries:
       Utilized scikit-learn libraries for loading datasets, splitting data, creating a model, and evaluating model performance.
  
  2) Loaded the Iris Dataset:
       Retrieved the Iris dataset, which includes measurements of iris flowers and their species.
  
  4) Selected Features and Labels: 
      Chose petal length and petal width as features (X). 
      Used the species of the iris flowers as labels (y).

  5) Split the Data into Training and Testing Sets:
       Divided the dataset into training (70%) and testing (30%) sets to evaluate the model's performance on unseen data.

  6) Initialized and Trained the Perceptron Model: 
      Created a Perceptron model with specified parameters. 
      Trained the model on the training data.

  7) Made Predictions on the Test Set:
       Used the trained model to predict the species of flowers in the test set.
  
  8) Calculated and Printed the Model's Accuracy: 
      Evaluated the accuracy of the model by comparing its predictions to the actual species in the test set. 
      Printed the accuracy as a percentage, indicating how well the model performed.

9) Displayed Examples of Predictions:
      Printed examples of the predicted and actual species for some samples from the test set along with their petal measurements to illustrate the model's performance.
