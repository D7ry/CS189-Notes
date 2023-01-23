# Classification

Steps:
1. Collect training data
2. Evaluate new data(**prediction**) 

## Nearest Neightbor v. Linear Classifier

Nearest neighbor always classifies training data right(100% accuracy rate)
Nearest neighbor usually is subject to **overfitting**

Linear Classifier classifies data based on a **hyperplane**[^f1]

## k-Nearest Neighbor Classifier

Take k points near the data, classify to the majority.

#Testing and Validation

2 kinds of errors:
1. Training Error: fraciton of training images not being classified correctly
2. **Test Set** Error: fraction of misclassified new images

**Outliers** - equivalent to edge cases  

**Overfitting** - when the test error deteriorates because the classifier becomes too sensitive to outlier or other spurious patterns, trying to avoid as much training error as possible.  

**Hyperparameter** Parameters for ML algorithms tweakable by human to controller overfitting/underfittin  
e.g. k-nearest neighbor's # of neighbors. Increasing&decreasing k affects overfitting/underfitting.

# Validation

**Validation set** - subset of data held back before training, to help select hyperparameters.

With the validation set, there are 3 sets used in ML:  
**training set** - model weights  
**validation set** - tune hyperparameters&choose among different models  
**test set** - as a final evaluation to be run once at the very end



[^f1]:a line that cuts data in 2 pieces