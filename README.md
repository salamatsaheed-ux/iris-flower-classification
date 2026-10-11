# iris-flower-classification
Classifying Iris flower species with Logistic Regression in scikit-learn, with evaluation and a simple prediction function.

A beginner machine learning project that classifies iris flowers into three species (setosa, versicolor, virginica) using Logistic Regression.

## Dataset

The Iris dataset from scikit-learn: 150 samples, 4 features each (sepal length, sepal width, petal length, petal width) and 3 species.

## Approach

1. Loaded the dataset
2. Split it into training (80%) and test (20%) sets
3. Trained a Logistic Regression model
4. Evaluated it with accuracy, a classification report and a confusion matrix
5. Added a `predict_flower()` function that predicts the species of a new flower

## Example

```python
predict_flower(5.1, 3.5, 1.4, 0.2)
# The species of flower is setosa
```

## How to Run

```bash
git clone https://github.com/salamatsaheed-ux/iris-flower-classification.git
cd iris-flower-classification
pip install scikit-learn matplotlib jupyter
jupyter notebook IrisDataset.ipynb
```

## Tools

Python · scikit-learn · Matplotlib · Jupyter Notebook

## Author

**Salamat Saheed Togun** ·
