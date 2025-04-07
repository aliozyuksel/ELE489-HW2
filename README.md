# Decision Trees

This repository contains an implementation of the decision tree algorithm with banknote authentication. The project creates different trees in which they have different parameters such as criterion, max_depth, min_samples_split.

Each tree has their own classification report and confusion matrix to visualize the effect of each parameter on model. Lastly, it contains feature importance. Each block of code in the notebook is explained in detail.


## Files

- `decision_tree.ipynb`: Jupyter Notebook that contains data analysis, usage of the decision trees, classification metrics etc.
- `data_banknote_authentication.txt`: Dataset used for training and testing.

## Data
 
- There are 4 features and 2 labels in the data.
- It also contains 1372 samples and none of them contains nan value.

## How to run

- To run this project, first install all the requirements given below.
- Then, put data_banknote_authentication.txt, decision_tree.ipynb in the same folder.
- Thereafter, each block in the decision_tree.ipynb can be run.

## Requirements

To run this project, install the required libraries using:

- matplotlib
- seaborn
- pandas
- numpy
- scikit-learn

You can install them by just writing the command below to your command promt.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

