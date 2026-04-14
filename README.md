![](https://komarev.com/ghpvc/?username=SSAKTHITSELVAN&color=blue)
---

# 📚 23AD601 — Optimization Techniques in Machine Learning
**Question Bank (Part-B 16-Mark Questions)** *Configured for Theory + Tutorial Split (3-1-0-4)*

## 📑 Exam Blueprint Overview
| Mark Split | Target Questions | Mapping |
| :--- | :--- | :--- |
| **8 + 8 Marks** | Q11, Q14, Q17, Q19 | Theory / Application Mix |
| **10 + 6 Marks** | Q12, Q13, Q18 | Conceptual Deep-Dive |
| **16M Undivided** | Q15, Q16, Q20 | Core Concepts & Case Studies |

---

## 🟢 Unit 1: Gradient Descent & Fundamentals (CO1)

### Q11 (8+8) — 🔴 High Probability
* **Q11(i) [8M]:** Explain the role of optimization in machine learning. Describe the Gradient Descent algorithm and its mathematical formulation. How does it minimize the loss function during model training?
* **Q11(ii) [8M]:** Compare Batch Gradient Descent, Stochastic Gradient Descent (SGD), and Mini-Batch Gradient Descent. Discuss their differences in terms of convergence speed, computational cost, and suitability for large datasets.

### Q12 (10+6) — 🔴 High Probability
* **Q12(i) [10M]:** Explain learning rate scheduling in gradient descent. Describe at least three scheduling strategies (step decay, exponential decay, cyclical learning rate) and analyze how each affects convergence.
* **Q12(ii) [6M]:** Explain convergence analysis of gradient descent. What conditions must be satisfied for gradient descent to converge to a global minimum?

### Alternatives & Practice
* **Alt Q11 [8M]:** Define optimization in ML. Explain the difference between local minima, global minima, and saddle points. How do gradient-based methods navigate these challenges?
* **Practice [8M]:** Explain the concept of vanishing and exploding gradients in deep learning. What techniques are used to mitigate them?

---

## 🔵 Unit 2: Convexity & Second-Order Methods (CO2 & CO3)

### Q13 (10+6) — 🔴 High Probability
* **Q13(i) [10M]:** Explain convex and non-convex optimization functions. Describe the properties of convex functions and explain why they are easier to solve. Illustrate with ML examples.
* **Q13(ii) [6M]:** Compare first-order (Gradient Descent) vs second-order (Newton's Method) optimization in terms of convergence rate and computational cost.

### Q14 (8+8) — 🔴 High Probability
* **Q14(i) [8M]:** Explain Newton's Method for optimization. Describe how it uses the Hessian matrix. What are the limitations, and how do Quasi-Newton Methods (BFGS) address them?
* **Q14(ii) [8M]:** Explain the L-BFGS (Limited-memory BFGS) algorithm. How does it overcome memory limitations? Describe its implementation using SciPy.

### Q16 — 💜 CASE STUDY 1 (GUARANTEED)
* **Q16 [16M]:** Implement and analyze **Newton's Method and the L-BFGS algorithm using SciPy** for a machine learning optimization problem. Describe the step-by-step process, compare convergence behavior, and evaluate performance on a sample dataset.

### Alternatives & Practice
* **Alt Q13 [10M]:** Explain the Conjugate Gradient Descent method. How does it improve over standard gradient descent using conjugate directions?
* **Practice [8M]:** Explain Trust-Region methods. How do they differ from line-search methods?

---

## 🟡 Unit 3: Regularization & Hyperparameter Tuning (CO3 & CO4)

### Q15 (16M) — 🔴 High Probability
* **Q15 [16M]:** Explain L1 (Lasso), L2 (Ridge), and Elastic Net regularization. Describe how each prevents overfitting, compare their effects on model coefficients, and explain when to prefer one over the other.

### Q17 (8+8) — 🔴 High Probability
* **Q17(i) [8M]:** Compare Grid Search, Random Search, and Bayesian Optimization as hyperparameter tuning strategies. Discuss trade-offs in search efficiency.
* **Q17(ii) [8M]:** Explain Genetic Algorithms (Selection, Crossover, Mutation). How are they applied to optimize hyperparameters in ML models?

### Q18 (10+6) — 🔴 High Probability
* **Q18(i) [10M]:** Explain Particle Swarm Optimization (PSO) and Simulated Annealing. Describe working principles and compare exploration vs. exploitation strategies.
* **Q18(ii) [6M]:** Explain Bayesian Optimization using a surrogate model (Gaussian Process). Why is it more efficient for high-dimensional spaces?

---

## 🔴 Unit 4: Advanced Neural Network Optimizers (CO5)

### Q19 (8+8) — 🔴 High Probability
* **Q19(i) [8M]:** Explain the Adam optimizer. Describe how it combines momentum and adaptive learning rates. Compare Adam with RMSprop and Adagrad.
* **Q19(ii) [8M]:** Explain the Nadam optimizer. How does it extend Adam using Nesterov momentum? Discuss scenarios where Nadam is preferred.

### Q20 — 💜 CASE STUDY 2 (GUARANTEED)
* **Q20 [16M]:** Describe the process of **hyperparameter tuning and optimization of deep learning models using TensorFlow**. Explain the application of Grid/Random/Bayesian search for tuning learning rate, batch size, and layers. Evaluate the impact of Adam vs RMSprop on performance.

### Alternatives & Practice
* **Alt Q19 [8M]:** Detail RMSprop and Adagrad. What problem does RMSprop solve that Adagrad cannot handle in long training runs?
* **Alt Q20 [16M]:** Describe PyTorch implementation of optimization algorithms. Write steps to configure Adam and SGD and compare their loss curves.
* **Practice [16M]:** Analyze the impact of optimizer choice on deep learning performance. How do momentum-based optimizers outperform vanilla SGD on complex loss surfaces?

---

### 💡 Final Prep Checklist:
1.  **Case Study Q16:** Practice the Python/SciPy code for L-BFGS.
2.  **Case Study Q20:** Memorize the tuning workflow in TensorFlow (Keras Tuner/Model.compile).
3.  **Comparisons:** Be ready with a table for *BGD vs SGD vs Mini-Batch* and *L1 vs L2*.

---
*© All copy rights are reserved under sa----*
