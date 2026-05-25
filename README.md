# 📐 Math for Data Science

A comprehensive collection of Jupyter Notebooks covering fundamental mathematical concepts for data science, based on _Essential Math for Data Science_ by Thomas Nield.

> 📖 _This repository is continuously updated with new topics._

## 📚 Topics Covered

### Calculus

| Notebook                      | Description                                                            |
| ----------------------------- | ---------------------------------------------------------------------- |
| `Basic_Math.ipynb`            | Number theory, operations, variables, functions, summations, exponents |
| `logrithms_eulerNumber.ipynb` | Logarithms, natural logarithms & Euler's number (e)                    |
| `calculus.ipynb`              | Limits, derivatives, partial derivatives, chain rule, integrals        |

### Probability

| Notebook                                 | Description                                                |
| ---------------------------------------- | ---------------------------------------------------------- |
| `01_probability_basics.ipynb`            | Probability fundamentals, terminology, axioms, simulations |
| `02_joint_union_probability.ipynb`       | Joint (AND), union (OR), mutually exclusive events         |
| `03_conditional_probability_bayes.ipynb` | Conditional probability & Bayes' theorem                   |
| `04_binomial_distribution.ipynb`         | Binomial distribution, PMF, CDF, A/B testing               |
| `05_beta_distribution.ipynb`             | Beta distribution, Bayesian updating                       |

### Statistics

| Notebook                                | Description                                    |
| --------------------------------------- | ---------------------------------------------- |
| `01_intro_and_sampling.ipynb`           | Data types, populations, samples, bias         |
| `02_descriptive_statistics.ipynb`       | Mean, median, mode, variance, std dev, IQR     |
| `03_normal_distribution_zscores.ipynb`  | Normal distribution, 68-95-99.7 rule, Z-scores |
| `04_clt_confidence_intervals.ipynb`     | Central Limit Theorem, confidence intervals    |
| `05_hypothesis_testing_pvalues.ipynb`   | Hypothesis testing, p-values, t-tests          |
| `06_t_distribution_small_samples.ipynb` | T-distribution, small samples, effect size     |

### Linear Algebra

| Notebook                                | Description                                                      |
| --------------------------------------- | ---------------------------------------------------------------- |
| `01_vectors.ipynb`                      | Vectors, operations, dot/cross product, span, linear independence |
| `02_linear_transformations.ipynb`       | Rotation, scaling, shearing, composition, inverse transforms      |
| `03_matrices_determinants.ipynb`        | Matrix operations, determinants, inverse, rank                    |
| `04_systems_of_equations.ipynb`         | Solving systems, least squares, linear regression connection      |
| `05_eigenvalues_eigenvectors.ipynb`     | Eigendecomposition, characteristic equation, PCA                  |

## 🛠️ Requirements

```bash
pip install sympy matplotlib numpy scipy pandas
```

## 📦 Dependencies

| Package      | Purpose                     |
| ------------ | --------------------------- |
| `sympy`      | Symbolic mathematics        |
| `numpy`      | Numerical computations      |
| `scipy`      | Statistical distributions   |
| `matplotlib` | Plotting and visualizations |
| `pandas`     | Data manipulation           |

## 🚀 Getting Started

1. Clone the repository
2. Open any notebook in Jupyter Notebook or VS Code
3. Run all cells sequentially
4. Experiment with the examples!

## 📂 Project Structure

```
MathforDS/
├── README.md
├── Essential Math for Data Science.pdf
├── Calculus/
│   ├── Basic_Math.ipynb
│   ├── logrithms_eulerNumber.ipynb
│   └── calculus.ipynb
├── Probability/
│   ├── 01_probability_basics.ipynb
│   ├── 02_joint_union_probability.ipynb
│   ├── 03_conditional_probability_bayes.ipynb
│   ├── 04_binomial_distribution.ipynb
│   └── 05_beta_distribution.ipynb
├── Statistics/
│   ├── 01_intro_and_sampling.ipynb
│   ├── 02_descriptive_statistics.ipynb
│   ├── 03_normal_distribution_zscores.ipynb
│   ├── 04_clt_confidence_intervals.ipynb
│   ├── 05_hypothesis_testing_pvalues.ipynb
│   └── 06_t_distribution_small_samples.ipynb
└── Linear_Algebra/
    ├── 01_vectors.ipynb
    ├── 02_linear_transformations.ipynb
    ├── 03_matrices_determinants.ipynb
    ├── 04_systems_of_equations.ipynb
    └── 05_eigenvalues_eigenvectors.ipynb
```

## 📝 License

This project is for educational purposes.

---

_Happy Learning! 🎓_
