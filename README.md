# Supervised and Unsupervised Learning

A beginner-friendly Machine Learning project that demonstrates the basic concepts of **supervised learning** and **unsupervised learning** through practical Python implementations in Jupyter Notebook.

This project was created to explore different types of machine learning models, understand how they work, and practice applying them to real datasets.

---

## Project Overview

Machine Learning is commonly divided into different learning approaches. This project focuses on two important types:

* **Supervised Learning** — learning from labeled data
* **Unsupervised Learning** — finding patterns in unlabeled data

The project includes practical examples of:

* Classification
* Regression
* Clustering
* Dimensionality reduction
* Data preprocessing
* Model training and evaluation
* Data visualization

Each notebook contains a separate learning task and shows how machine learning algorithms can be implemented step by step.

---

## Repository Structure

```text
Supervisor-Unsupervisor-Learning/
│
├── classification.ipynb
├── regression.ipynb
├── unsupervisor.ipynb
└── README.md
```

---

## Notebook Descriptions

| Notebook               | Description                                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `classification.ipynb` | Demonstrates supervised learning for classification tasks, where the goal is to predict a category or class label. |
| `regression.ipynb`     | Demonstrates supervised learning for regression tasks, where the goal is to predict a continuous numerical value.  |
| `unsupervisor.ipynb`   | Demonstrates unsupervised learning techniques such as clustering and dimensionality reduction.                     |

---

## Learning Approaches Covered

### 1. Supervised Learning

Supervised learning uses labeled data. This means that each training example already has a known correct answer.

In this project, supervised learning is shown through:

* Classification
* Regression

#### Classification

Classification is used when the model needs to predict a category.

Examples:

* Predicting whether an email is spam or not spam
* Predicting the type of flower
* Predicting whether a customer will buy a product

Common algorithms:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine
* K-Nearest Neighbors

#### Regression

Regression is used when the model needs to predict a continuous numerical value.

Examples:

* Predicting house prices
* Predicting student scores
* Predicting temperature
* Predicting sales

Common algorithms:

* Linear Regression
* Polynomial Regression
* Decision Tree Regressor
* Random Forest Regressor

---

### 2. Unsupervised Learning

Unsupervised learning works with unlabeled data. The model does not receive correct answers in advance. Instead, it tries to find hidden patterns, groups, or structures in the data.

In this project, unsupervised learning is shown through:

* Clustering
* Dimensionality reduction

#### Clustering

Clustering groups similar data points together.

Examples:

* Grouping customers by behavior
* Finding similar documents
* Segmenting users based on activity

Common algorithms:

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN

#### Dimensionality Reduction

Dimensionality reduction reduces the number of features while keeping the most important information.

It is useful for:

* Data visualization
* Noise reduction
* Faster model training
* Understanding high-dimensional datasets

Common algorithms:

* PCA
* t-SNE
* UMAP

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Main Concepts Practiced

This project helps practice the following Machine Learning concepts:

* Loading datasets
* Understanding dataset structure
* Data cleaning
* Feature selection
* Splitting data into training and testing sets
* Training machine learning models
* Making predictions
* Evaluating model performance
* Visualizing results
* Comparing different learning approaches

---

## Model Evaluation

Different evaluation methods are used depending on the type of task.

### Classification Metrics

Classification models can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

### Regression Metrics

Regression models can be evaluated using:

* Mean Absolute Error
* Mean Squared Error
* Root Mean Squared Error
* R² Score

### Clustering Evaluation

Clustering results can be analyzed using:

* Visual inspection
* Cluster plots
* Inertia
* Silhouette score

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/mrGwynbleidd/Supervisor-Unsupervisor-Learning.git
```

### 2. Open the Project Folder

```bash
cd Supervisor-Unsupervisor-Learning
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib scikit-learn notebook
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open Any Notebook

You can open and run:

```text
classification.ipynb
regression.ipynb
unsupervisor.ipynb
```

Run the cells one by one to see the full implementation and results.

---

## Example Workflow

A typical machine learning workflow in this project follows these steps:

```text
1. Import libraries
2. Load the dataset
3. Explore the data
4. Prepare the data
5. Choose a model
6. Train the model
7. Make predictions
8. Evaluate the results
9. Visualize the outcome
10. Write observations
```

---

## Educational Purpose

This project was created as a learning project for understanding the foundations of Machine Learning.

The main goal is not only to run algorithms, but also to understand:

* When to use supervised learning
* When to use unsupervised learning
* How classification differs from regression
* How clustering finds hidden groups
* How dimensionality reduction helps simplify data
* How to evaluate model performance

---

## Possible Improvements

Future improvements may include:

* Adding more datasets
* Adding more machine learning algorithms
* Creating a separate `requirements.txt` file
* Adding comments and explanations inside each notebook
* Adding visual comparison between models
* Improving notebook structure
* Adding a final summary notebook
* Adding saved model examples
* Adding hyperparameter tuning
* Adding cross-validation

---

## Recommended Folder Improvements

For a more professional structure, the repository can later be organized like this:

```text
Supervisor-Unsupervisor-Learning/
│
├── notebooks/
│   ├── classification.ipynb
│   ├── regression.ipynb
│   └── unsupervised_learning.ipynb
│
├── data/
│   └── README.md
│
├── images/
│   └── README.md
│
├── requirements.txt
└── README.md
```

This structure makes the repository cleaner and easier to understand.

---

## Notes

The repository name currently uses the words **Supervisor** and **Unsupervisor**, but the standard Machine Learning terms are:

```text
Supervised Learning
Unsupervised Learning
```

For a more professional GitHub portfolio, the repository name could be renamed to:

```text
Supervised-Unsupervised-Learning
```

or

```text
ML-Learning-Basics
```

---

## Author

Created as a beginner Machine Learning learning project.

GitHub Repository: `mrGwynbleidd/Supervisor-Unsupervisor-Learning`

---

## License

This project is for educational purposes.
