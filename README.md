# Decision Tree Classifier on Iris Dataset

## Project Overview
This project implements a Decision Tree Classifier to classify Iris flower species (Setosa, Versicolor, Virginica) based on sepal and petal measurements using Python and scikit-learn.

The Decision Tree model is a supervised learning algorithm that is easy to interpret and visualize, making it ideal for understanding how classification decisions are made.

## Dataset
The famous Iris dataset contains 150 samples with 4 features each:  
- Sepal length (cm)  
- Sepal width (cm)  
- Petal length (cm)  
- Petal width (cm)

The target classes are three Iris species:
- Setosa  
- Versicolor  
- Virginica  

## Features
- Load and explore the dataset using pandas.  
- Split data into training and testing sets.  
- Train a Decision Tree classifier.  
- Evaluate model performance with classification report and confusion matrix.  
- Visualize the trained decision tree.  
- Save the trained model for future use.

## Getting Started

### Prerequisites
- Python 3.x  
- scikit-learn  
- pandas  
- matplotlib  
- joblib  

You can install the required libraries using:

```bash
pip install scikit-learn pandas matplotlib joblib

Running the Notebook
Open the Jupyter notebook Decision_tree_classifier_for_Iris_dataset.ipynb in Jupyter or Google Colab, and run the cells sequentially.

Files
Decision_tree_classifier_for_Iris_dataset.ipynb: Jupyter notebook with full implementation.

decision_tree_iris.joblib: Saved trained model file.

decision_tree_iris.png: Visualization of the trained decision tree.

Results
The model achieves high accuracy on the Iris dataset and the visualization clearly shows the decision rules based on feature thresholds.

Future Work
Hyperparameter tuning (e.g., max_depth, min_samples_split)

Cross-validation and GridSearchCV for better model selection

Experiment with ensemble methods like Random Forests
