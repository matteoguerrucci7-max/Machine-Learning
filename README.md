
# 🧠 Machine Learning

Welcome to my Machine Learning repository!

### 🌟 The Vision
The core purpose of this project is to demonstrate how something as abstract and imaginative as mathematics serves as the absolute foundation for the most powerful and widely used learning tools of our time. Instead of treating algorithms as black boxes, these notebooks explore the underlying geometry, linear algebra, probability, statistical learning theory and calculus, bridging the gap between rigorous theory and clean NumPy implementations.

## 📚 Contents

1. **[01. Statistical Learning Theory](./01_statistical_learning_theory.ipynb)**
   * Expected Risk, Empirical Risk Minimization (ERM), and the Bias-Variance Tradeoff.
2. **[02. PAC Learning & VC Dimension](./02_pac_and_vc_dimensions.ipynb)**
   * Consistent/Agnostic Learners, Shattering, and Sample Complexity bounds.
3. **[03. Linear Algebra & Geometry](./03_linear_algebra_and_geometry.ipynb)**
   * Vector Spaces, Eigendecomposition, and the Spectral Theorem applied to data.
4. **[04. Principal Component Analysis](./04_pca.ipynb)**
   * Principal Component Analysis and Probabilistic PCA.
5. **[05. Gaussian Mixture Models](./05_gaussian_mixture_models.ipynb)**
   * Clustering, Gaussian Mixture Models.
6. **[06. Linear and Polynomial Regression](./06_linear_regression.ipynb)**
   * Linear Regression, Polynomial Regression, Ridge Regression.
7. **[07. Logistic Regression](./07_logistic_regression.ipynb)**
   * Sigmoid Link, Maximum Likelihood, Newton-Raphson/IRLS, Softmax Regression, Generative vs. Discriminative Classifiers.
8. **[08. Support Vector Machines & Kernel Methods](./08_svm_and_kernel_methods.ipynb)**
   * KKT conditions, SVM, Kernel Methods, Gaussian Kernel.
9. **[09. Decision Trees, Random Forests & Boosting](./09_decision_trees_random_forest_boosting.ipynb)**
   * Decision Trees, Random Forests, AdaBoost, Gradient Boosting, XGBoost.
10. **[10. Model Selection and Validation](./10_model_selection_and_validation.ipynb)**
    * Validation Set, K-Fold Cross-Validation, Selection Bias, and why the Test Set is used once.

## ⚙️ Setup
```bash
pip install -r requirements.txt
```
Each notebook is meant to be run top to bottom (`Restart Kernel & Run All`) so the committed outputs always match the code.

## 🛠️ Tools & Libraries
* **Python 3**
* **NumPy** (Heavy focus on vectorized mathematical operations)
* **Matplotlib** (Geometric and statistical visualizations)
* **SciPy & scikit-learn** (statistical distributions, baseline models for comparison)
* **XGBoost** (comparison with the from-scratch implementation in notebook 09)

## 📄 License
[MIT](./LICENSE) — feel free to learn from, fork, or reuse any of this.

---
*Created by Matteo Guerrucci*
