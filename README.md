# Machine Learning Algorithms

A comprehensive collection of Machine Learning algorithms implemented during my Master's degree program. This repository showcases hands-on implementations of supervised, unsupervised, and advanced ML techniques using Python and scikit-learn.

## 📚 About This Repository

This repository contains Colab notebooks demonstrating various machine learning algorithms learned and implemented throughout my graduate studies. Each notebook includes theoretical explanations, practical implementations, and real-world applications of the algorithms.

## 🎓 Academic Background

**Program**: Master's Degree  
**Focus Area**: Artificial Intelligence & Machine Learning 
**Duration**: 2 years of intensive study and implementation

## 📑 Table of Contents

- [Supervised Learning](#supervised-learning)
- [Unsupervised Learning](#unsupervised-learning)
- [Model Optimization](#model-optimization)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)

## 🤖 Algorithms Implemented

### Supervised Learning

#### Regression Algorithms
- **[Linear Regression](ML1_LinearRegiression.ipynb)** - Simple linear regression for continuous variable prediction
- **[Multivariate Linear Regression](MULTIVARIATE.ipynb)** - Multiple feature regression analysis
- **[Multivariate Linear Regression (Extended)](multivariatelinearregression.ipynb)** - Advanced multivariate techniques

#### Classification Algorithms
- **[Logistic Regression](LogisticRegression.ipynb)** - Binary and multiclass classification
- **[Decision Tree](DecisionTree.ipynb)** - Tree-based classification and regression
- **[Support Vector Machine (SVM)](SuppoortVectorMachineExample.ipynb)** - Margin-based classification
- **[SVM with ROC-AUC Analysis](SupportVectorMachineROC_AUC.ipynb)** - Performance evaluation using ROC curves
- **[SVM vs Logistic Regression](SupportVectorMachine_Logistic.ipynb)** - Comparative analysis

#### Probabilistic Models
- **[Naive Bayes (Multinomial)](NaiveBayesMultinomial.ipynb)** - Text classification and probability-based predictions
- **[Complement Naive Bayes](COMPLEMENT_NB.ipynb)** - Enhanced NB for imbalanced datasets

### Unsupervised Learning

#### Clustering Algorithms
- **[K-Means Clustering](K_MeansClustering1.ipynb)** - Centroid-based clustering
- **[Finding Optimal K Value](FINDING__k_value_AND_cluster2.ipynb)** - Elbow method and silhouette analysis
- **[DBSCAN Clustering](DBSCAN_CLUSTERING3.ipynb)** - Density-based spatial clustering
- **[Hierarchical Clustering](HierarchicalClustering.ipynb)** - Agglomerative and divisive clustering

### Model Optimization

- **[Regularization Techniques](Regularization.ipynb)** - Ridge, Lasso, and Elastic Net for overfitting prevention

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook / Google Colab**
- **Libraries**:
  - NumPy - Numerical computing
  - Pandas - Data manipulation
  - Scikit-learn - Machine learning algorithms
  - Matplotlib - Data visualization
  - Seaborn - Statistical plotting
  - SciPy - Scientific computing

## 📊 Key Concepts Covered

### Regression Analysis
- Simple and multiple linear regression
- Polynomial regression
- Residual analysis
- R-squared and adjusted R-squared

### Classification Techniques
- Binary and multiclass classification
- Decision boundaries
- Confusion matrix analysis
- Precision, recall, and F1-score
- ROC-AUC curves

### Clustering Methods
- Centroid-based clustering (K-Means)
- Density-based clustering (DBSCAN)
- Hierarchical clustering dendrograms
- Cluster evaluation metrics

### Model Evaluation
- Train-test split
- Cross-validation
- Hyperparameter tuning
- Overfitting and underfitting
- Regularization (L1, L2)

## 🚀 Getting Started

### Prerequisites
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

### Running the Notebooks

1. **Clone the repository**
```bash
git clone https://github.com/Manya123-max/Machine-Learning-Algorithms.git
cd Machine-Learning-Algorithms
```

2. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

3. **Or open in Google Colab**
- Upload the `.ipynb` files to Google Drive
- Open with Google Colaboratory

## 📈 Learning Outcomes

Through these implementations, I have gained proficiency in:

- ✅ Understanding mathematical foundations of ML algorithms
- ✅ Implementing algorithms from scratch and using libraries
- ✅ Data preprocessing and feature engineering
- ✅ Model selection and evaluation
- ✅ Handling imbalanced datasets
- ✅ Interpreting model performance metrics
- ✅ Applying appropriate algorithms to real-world problems
- ✅ Optimizing model performance through regularization

## 📝 Project Structure

```
Machine-Learning-Algorithms/
│
├── Regression/
│   ├── ML1_LinearRegiression.ipynb
│   ├── MULTIVARIATE.ipynb
│   └── multivariatelinearregression.ipynb
│
├── Classification/
│   ├── LogisticRegression.ipynb
│   ├── DecisionTree.ipynb
│   ├── SuppoortVectorMachineExample.ipynb
│   ├── SupportVectorMachineROC_AUC.ipynb
│   ├── SupportVectorMachine_Logistic.ipynb
│   ├── NaiveBayesMultinomial.ipynb
│   └── COMPLEMENT_NB.ipynb
│
├── Clustering/
│   ├── K_MeansClustering1.ipynb
│   ├── FINDING__k_value_AND_cluster2.ipynb
│   ├── DBSCAN_CLUSTERING3.ipynb
│   └── HierarchicalClustering.ipynb
│
├── Optimization/
│   └── Regularization.ipynb
│
└── README.md
```

## 🔍 Notable Implementations

### 1. Support Vector Machine Analysis
Comprehensive implementation including kernel tricks, margin optimization, and comparative analysis with logistic regression using ROC-AUC metrics.

### 2. Clustering Ensemble
Complete clustering workflow from finding optimal K values using elbow method to advanced density-based and hierarchical clustering techniques.

### 3. Regularization Study
In-depth exploration of L1 (Lasso) and L2 (Ridge) regularization for preventing overfitting in linear models.

## 📧 Contact

**Manya**  

## 📄 License

This project is open source and available for educational purposes.
