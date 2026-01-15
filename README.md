# Machine-learning-algorithms-comparing

This project uses machine learning to classify particles as Gamma or Hadron based on data from the MAGIC Gamma Telescope.

## The code:

1.Loads and prepares the dataset
2.Balances the classes to avoid bias
3.Trains different classification models
4.Compares their performance using standard metrics
5.Visualizes the results

## Models used:
-Decision Tree
-Naïve Bayes
-Random Forest (with parameter tuning)
-AdaBoost (with parameter tuning)

## Dataset:
File: magic04.data (you can get from Kaggle.com)
10 numerical features
### Target class:
    Gamma → 1
    Hadron → 0
The dataset is balanced by downsampling the Gamma class.

## How the code works:

1.Splits the data into training (70%) and testing (30%)
2.Trains each model on the training set
### 3.Evaluates models using:
    Accuracy
    Precision
    Recall
    F1-score
### 4.Plots:
    Model comparison chart
    Confusion matrices for all models
    
## Results (Test Set):
Best model: Random Forest
Random Forest achieved the highest accuracy and F1-score compared to the other models.

