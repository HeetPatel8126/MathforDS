# Math for Data Science

> A comprehensive, hands-on collection of Jupyter Notebooks covering the essential mathematical foundations for data science — from basic calculus to neural networks.

<p align="center">
  <strong>Based on <em>Essential Math for Data Science</em> by Thomas Nield</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
</p>

---

## Topics Covered

### Calculus

| Notebook | Description |
| --- | --- |
| `Basic_Math.ipynb` | Number theory, operations, variables, functions, summations, exponents |
| `logrithms_eulerNumber.ipynb` | Logarithms, natural logarithms & Euler's number (*e*) |
| `calculus.ipynb` | Limits, derivatives, partial derivatives, chain rule, integrals |

---

### Probability

| Notebook | Description |
| --- | --- |
| `01_probability_basics.ipynb` | Probability fundamentals, terminology, axioms, simulations |
| `02_joint_union_probability.ipynb` | Joint (AND), union (OR), mutually exclusive events |
| `03_conditional_probability_bayes.ipynb` | Conditional probability & Bayes' theorem |
| `04_binomial_distribution.ipynb` | Binomial distribution, PMF, CDF, A/B testing |
| `05_beta_distribution.ipynb` | Beta distribution, Bayesian updating |

---

### Statistics

| Notebook | Description |
| --- | --- |
| `01_intro_and_sampling.ipynb` | Data types, populations, samples, bias |
| `02_descriptive_statistics.ipynb` | Mean, median, mode, variance, std dev, IQR |
| `03_normal_distribution_zscores.ipynb` | Normal distribution, 68-95-99.7 rule, Z-scores |
| `04_clt_confidence_intervals.ipynb` | Central Limit Theorem, confidence intervals |
| `05_hypothesis_testing_pvalues.ipynb` | Hypothesis testing, p-values, t-tests |
| `06_t_distribution_small_samples.ipynb` | T-distribution, small samples, effect size |

---

### Linear Algebra

| Notebook | Description |
| --- | --- |
| `01_vectors.ipynb` | Vectors, operations, dot/cross product, span, linear independence |
| `02_linear_transformations.ipynb` | Rotation, scaling, shearing, composition, inverse transforms |
| `03_matrices_determinants.ipynb` | Matrix operations, determinants, inverse, rank |
| `04_systems_of_equations.ipynb` | Solving systems, least squares, linear regression connection |
| `05_eigenvalues_eigenvectors.ipynb` | Eigendecomposition, characteristic equation, PCA |

---

### Linear Regression

| Notebook | Description |
| --- | --- |
| `01_basic_linear_regression.ipynb` | Intro to linear regression, residuals, and sum of squares |
| `02_finding_best_fit_line.ipynb` | Closed form equation, inverse matrices, gradient descent |
| `03_correlation_and_evaluation.ipynb` | Pearson correlation, r-squared, p-values, prediction intervals |
| `04_multiple_linear_regression.ipynb` | Multivariable linear regression |

---

### Logistic Regression

| Notebook | Description |
| --- | --- |
| `01_understanding_logistic_regression.ipynb` | Intro, logistic function, fitting the logistic curve |
| `02_multivariable_logistic_regression.ipynb` | Multivariable logistic regression, understanding log-odds |
| `03_r_squared_and_p_values.ipynb` | R-squared and p-values for logistic regression |
| `04_train_test_splits_and_confusion_matrices.ipynb` | Train/test splits, confusion matrices |
| `05_roc_auc_and_class_imbalance.ipynb` | ROC/AUC curve and class imbalance strategies |

---

### Neural Networks

| Notebook | Description |
| --- | --- |
| `01_intro_and_simple_neural_network.ipynb` | What neural networks are, when to use them, network structure, weights & biases |
| `02_activation_functions.ipynb` | ReLU, Sigmoid, Tanh, Softmax — what they do and when to use each |
| `03_forward_propagation.ipynb` | Step-by-step forward pass, matrix multiplication walkthrough |
| `04_backpropagation_and_training.ipynb` | Chain rule, backpropagation, SGD training loop, 97-99% accuracy |
| `05_scikit_learn_and_limitations.ipynb` | MLPClassifier in scikit-learn, overfitting, and real-world limitations |

---

## Project Structure

```
MathforDS/
├── README.md
├── Essential Math for Data Science.pdf
│
├── Calculus/
│   ├── Basic_Math.ipynb
│   ├── logrithms_eulerNumber.ipynb
│   └── calculus.ipynb
│
├── Probability/
│   ├── 01_probability_basics.ipynb
│   ├── 02_joint_union_probability.ipynb
│   ├── 03_conditional_probability_bayes.ipynb
│   ├── 04_binomial_distribution.ipynb
│   └── 05_beta_distribution.ipynb
│
├── Statistics/
│   ├── 01_intro_and_sampling.ipynb
│   ├── 02_descriptive_statistics.ipynb
│   ├── 03_normal_distribution_zscores.ipynb
│   ├── 04_clt_confidence_intervals.ipynb
│   ├── 05_hypothesis_testing_pvalues.ipynb
│   └── 06_t_distribution_small_samples.ipynb
│
├── Linear_Algebra/
│   ├── 01_vectors.ipynb
│   ├── 02_linear_transformations.ipynb
│   ├── 03_matrices_determinants.ipynb
│   ├── 04_systems_of_equations.ipynb
│   └── 05_eigenvalues_eigenvectors.ipynb
│
├── Linear_Regression/
│   ├── 01_basic_linear_regression.ipynb
│   ├── 02_finding_best_fit_line.ipynb
│   ├── 03_correlation_and_evaluation.ipynb
│   └── 04_multiple_linear_regression.ipynb
│
├── Logistic_Regression/
│   ├── 01_understanding_logistic_regression.ipynb
│   ├── 02_multivariable_logistic_regression.ipynb
│   ├── 03_r_squared_and_p_values.ipynb
│   ├── 04_train_test_splits_and_confusion_matrices.ipynb
│   └── 05_roc_auc_and_class_imbalance.ipynb
│
└── Neural_Network/
    ├── 01_intro_and_simple_neural_network.ipynb
    ├── 02_activation_functions.ipynb
    ├── 03_forward_propagation.ipynb
    ├── 04_backpropagation_and_training.ipynb
    └── 05_scikit_learn_and_limitations.ipynb
```

---

## Requirements

```bash
pip install sympy matplotlib numpy scipy pandas scikit-learn
```

## Dependencies

| Package | Purpose |
| --- | --- |
| `sympy` | Symbolic mathematics |
| `numpy` | Numerical computations |
| `scipy` | Statistical distributions |
| `matplotlib` | Plotting and visualizations |
| `pandas` | Data manipulation |
| `scikit-learn` | Machine learning models & utilities |

---

## Getting Started

1. **Clone** the repository
   ```bash
   git clone https://github.com/HeetPatel8126/MathforDS.git
   ```
2. **Install** dependencies
   ```bash
   pip install sympy matplotlib numpy scipy pandas scikit-learn
   ```
3. **Open** any notebook in Jupyter Notebook or VS Code
4. **Run** all cells sequentially
5. **Experiment** with the examples!

> **Tip:** Start from `Calculus/` and work your way through in order — each topic builds on the previous one.

---

## Learning Path

```
Calculus → Probability → Statistics → Linear Algebra → Linear Regression → Logistic Regression → Neural Networks
```

Each chapter builds on concepts from the previous ones. For example:
- **Neural Networks** use gradient descent from *Linear Regression*, the logistic function from *Logistic Regression*, matrix multiplication from *Linear Algebra*, and the chain rule from *Calculus*.

---

## License

This project is for educational purposes.

---

<p align="center">
  <em>Happy Learning!</em>
</p>
