# ACM Work — Machine Learning Foundations

A collection of hands-on Machine Learning notebooks covering **data exploration, supervised learning, and unsupervised learning algorithms**.

This repository was created as a practical learning space to understand how different ML algorithms work, how they are applied to datasets, and how their results can be analyzed.

---

## 📌 What's Inside

The repository currently covers:

| Topic                     | Notebook              |
| ------------------------- | --------------------- |
| Exploratory Data Analysis | `eda.ipynb`           |
| K-Nearest Neighbors       | `knn.ipynb`           |
| K-Means Clustering        | `kmeans.ipynb`        |
| Decision Trees            | `decisiontrees.ipynb` |
| Random Forest             | `RandomForest.ipynb`  |
| Naive Bayes               | `Naivebayes.ipynb`    |

---

## 🧠 Topics Covered

### Exploratory Data Analysis

The EDA notebook focuses on understanding a dataset before applying machine learning models.

Key concepts include:

* Data inspection
* Data preprocessing
* Feature exploration
* Statistical analysis
* Data visualization
* Identifying patterns in the dataset

---

### K-Nearest Neighbors

The KNN notebook explores instance-based classification using the idea that similar data points tend to belong to similar classes.

Concepts covered include:

* Distance-based classification
* Choosing `K`
* Nearest-neighbor selection
* Classification using KNN

---

### K-Means Clustering

The K-Means notebook explores **unsupervised learning** and grouping data points into clusters.

Concepts covered include:

* Cluster initialization
* Centroid assignment
* Updating centroids
* Iterative clustering
* Understanding cluster formation

---

### Decision Trees

The Decision Tree notebook explores tree-based supervised learning.

Concepts include:

* Splitting data
* Decision nodes
* Leaf nodes
* Feature-based decisions
* Classification using decision trees

---

### Random Forest

The Random Forest notebook explores ensemble learning by combining multiple decision trees.

Concepts include:

* Ensemble learning
* Multiple decision trees
* Random feature selection
* Combining predictions
* Understanding the advantage of ensembles

---

### Naive Bayes

The Naive Bayes notebook explores probabilistic classification based on Bayes' theorem and the assumption of conditional independence between features.

Concepts include:

* Bayes' theorem
* Prior probability
* Conditional probability
* Posterior probability
* Probabilistic classification

---

## 🔬 Learning Approach

The notebooks are organized around a practical ML workflow:

```text
Dataset
   ↓
Data Understanding
   ↓
Exploratory Data Analysis
   ↓
Preprocessing
   ↓
Model Selection
   ↓
Training
   ↓
Prediction
   ↓
Evaluation
```

The goal is not just to use ML libraries, but to understand the intuition and workflow behind commonly used algorithms.

---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📂 Repository Structure

```text
ACM-work/
│
├── eda.ipynb
├── knn.ipynb
├── kmeans.ipynb
├── decisiontrees.ipynb
├── RandomForest.ipynb
├── Naivebayes.ipynb
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/KhyathiNoothi/ACM-work.git
cd ACM-work
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install the required libraries

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook and run the cells sequentially.

---

## 📚 Purpose

This repository serves as a practical record of my Machine Learning learning journey, with individual notebooks dedicated to understanding different algorithms and concepts.

Rather than treating ML models as black boxes, the notebooks provide hands-on experimentation with the algorithms and their workflows.

---

## 🔭 Future Improvements

Possible extensions to this repository include:

* Add model evaluation metrics consistently across notebooks
* Compare multiple algorithms on the same dataset
* Add visual explanations for algorithms
* Include hyperparameter tuning
* Add cross-validation experiments
* Add more ML algorithms such as:

  * Logistic Regression
  * SVM
  * Gradient Boosting
  * XGBoost
  * PCA
  * DBSCAN
  * Hierarchical Clustering
* Organize notebooks into structured learning modules

---


---

⭐ If you find this repository useful for learning ML fundamentals, consider starring the repository.
