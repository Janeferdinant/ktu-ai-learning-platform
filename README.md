# APJ Abdul Kalam Technological University (KTU)
## AI & Data Science: Interactive Learning, Algorithm Labs, Numerical Solvers & Examination Answer Keys
**Course Code:** GNEST305 • **Programme:** B.Tech (2024 Scheme) • **Credits:** 4 (L:T:P = 3:1:0:0)  
**Author & Course Instructor:** **Jane Rose N F**, Assistant Professor, Department of Computer Science & Engineering (CSE)  
**Live Deployment:** [https://ktu-ai-learning-platform.vercel.app](https://ktu-ai-learning-platform.vercel.app)  
**GitHub Repository:** [https://github.com/Janeferdinant/ktu-ai-learning-platform](https://github.com/Janeferdinant/ktu-ai-learning-platform)  

---

## 🌟 Executive Overview
This repository hosts a state-of-the-art academic learning and examination preparation platform tailored specifically for the **APJ Abdul Kalam Technological University (KTU)** Artificial Intelligence and Data Science curriculum (Course Code: `GNEST305`, 2024 Scheme).

Designed by **Jane Rose N F** (Assistant Professor, CSE Dept.), the platform bridges abstract mathematical formulations with real-time visual canvases, gamified challenges, step-by-step solved numerical calculations, formal algorithmic blueprints, and official KTU End Semester Examination answer keys with marking rubrics.

```
                              KTU AI & DS PORTAL (GNEST305)
                                            │
        ┌───────────────────┬───────────────┴───────────────┬───────────────────┐
        ▼                   ▼                               ▼                   ▼
┌───────────────┐   ┌───────────────┐               ┌───────────────┐   ┌───────────────┐
│  5 Algorithm  │   │   4 Concept   │               │  7 Numerical  │   │ Official Exam │
│  Visual Labs  │   │ Mastery Games │               │ Worked Solvers│   │ & Answer Keys │
└───────────────┘   └───────────────┘               └───────────────┘   └───────────────┘
```

---

## 🏛️ Syllabus Coverage (Strict 44-Hour Curriculum)

| Module | Contact Hours | Focus & Core Algorithms | Course Outcome | Bloom's Levels |
|---|---|---|---|---|
| **Module 1** | 11 Hours | Search, Perceptrons, MLPs, Activation & Loss Functions, Backprop | **CO1** | Level 1, 2, 3 |
| **Module 2** | 11 Hours | Linear Algebra, Eigenvalues/Eigenvectors, SVD, PCA, Covariance | **CO2** | Level 2, 3, 4 |
| **Module 3** | 11 Hours | Probability, Bayes' Theorem, Naive Bayes, MLE, Gaussian Dist. | **CO3** | Level 2, 3 |
| **Module 4** | 11 Hours | Linear/Logistic Regression, K-Means, Confusion Matrix, ROC-AUC | **CO4** | Level 2, 3, 4 |

---

## 🔬 Core Interactive Components

### 1. Interactive Algorithm Visualizer Labs
- **Linear Perceptron Lab**: Real-time Cartesian coordinate space ($w_1 x_1 + w_2 x_2 + b = 0$) with live sliders. Features **1 Epoch Step** and **Auto-Converge** execution of Rosenblatt's learning rule.
- **K-Means Clustering & Voronoi Partitioner**: Dynamically tune $K$ (2 to 5), randomize data clusters, and step through the **Expectation-Maximization** cycle (Voronoi region assignment + centroid mean migration) with live Inertia (SSE) calculation.
- **SVD & PCA Projection Lab**: Correlated 2D data cloud with Principal Component eigenvectors ($v_1, v_2$) scaled by singular values $\sqrt{\lambda_1}, \sqrt{\lambda_2}$. Toggle projection to 1D subspace to inspect variance retained and reconstruction error.
- **Bayes Diagnostic Simulator**: Sliders for Prior $P(D)$, Sensitivity $P(+|D)$, and False Positive Rate $P(+|D^c)$ illustrating the **Base Rate Fallacy** and natural frequency breakdown across 10,000 components.
- **Gradient Descent Optimization Surface**: 2D quadratic cost surface $J(w_1, w_2)$ with adjustable learning rate $\eta$ and momentum $\beta$, showing convergence trajectories, oscillations, or divergence.

### 2. 🧮 Numerical Problems & Worked-Out Solutions
Includes 7 complete numerical problems with full arithmetic working, step-by-step formula substitutions, and KTU mark allocations:
1. **Module 1 — Perceptron Learning Rule Updates**: Linear net input $z$, threshold activation, error calculation $e = y - \hat{y}$, and updated weights $w' = w + \eta e x$ and bias $b'$.
2. **Module 2 — Matrix Eigenvalues & Eigenvectors**: Characteristic equation $\det(A - \lambda I) = 0$, quadratic root solving, and normalized basis eigenvectors.
3. **Module 2 — SVD Decomposition**: Gram matrix $X X^T$, singular values $\sigma_i = \sqrt{\lambda_i}$, and singular value matrix $\Sigma$.
4. **Module 3 — Multi-Machine Defect Probability**: Law of Total Probability for denominator evidence and Bayes' inversion for machine failure attribution.
5. **Module 4 — Ordinary Least Squares (OLS) Regression**: Deviation product tables, slope $w_1 = \frac{\sum (x - \bar{x})(y - \bar{y})}{\sum (x - \bar{x})^2}$, intercept $w_0$, and future wear prediction.
6. **Module 4 — Confusion Matrix Metrics**: Accuracy, Precision, Recall, Specificity, and F1-Score calculation from contingency tables.
7. **Interactive Live Bayes Calculator**: Dynamic inputs for priors and sensor noise with real-time step-by-step arithmetic.

### 3. ⚙️ Algorithm Blueprints & Complexity Guide
Formal algorithmic pseudocode, mathematical invariants, convergence conditions, and Big-O complexity bounds:
- **Algorithm 1:** Rosenblatt's Perceptron Learning Algorithm (PLA) — $O(k \cdot n \cdot d)$.
- **Algorithm 2:** Multi-Layer Perceptron (MLP) Error Backpropagation with Gradient Descent.
- **Algorithm 3:** Principal Component Analysis (PCA) via Covariance Eigendecomposition & SVD — $O(n \cdot d^2 + d^3)$.
- **Algorithm 4:** K-Means Clustering (Lloyd's Heuristic) — $O(t \cdot K \cdot n \cdot d)$.

### 4. 📝 KTU Model Examination Paper & Official Valuation Answer Key
Authentic End Semester Examination format (60 Marks, 2.5 Hours):
- **Part A (Short Answer — 8 Questions × 3 Marks = 24 Marks, All Compulsory)**:
  - Full questions across Modules 1 to 4 with **step-by-step marking rubrics** (e.g. `[1 Mark: Formula | 1 Mark: Substitution | 1 Mark: Final Answer]`).
- **Part B (Long Answer — 4 Questions × 9 Marks = 36 Marks, Internal Choice)**:
  - Deep mathematical derivations (e.g., Binary Cross-Entropy gradient derivation with Sigmoid activation, $2 \times 2$ SVD matrices, PCA projection, OLS Normal Equation $w = (X^T X)^{-1} X^T y$).
  - Official Scheme of Valuation with mark distribution rubrics.

### 5. 🎮 Gamified Concept Mastery Arena
- 🎮 **Hyperplane Slicer (Perceptron Boundary Arcade)**: 30-second countdown to rotate and shift the decision boundary to achieve 100% linear classification before time expires.
- 🎮 **Eigen-Hunter (Invariance Quest)**: Rotate test vector $v$ on the unit circle until transformed vector $Av$ is collinear with $v$, capturing the invariant **Eigenvector** and its **Eigenvalue $\lambda$**.
- 🎮 **Bayes Detective (Industrial Diagnostics Mystery)**: Solve a real-world CNC bearing vibration alarm using Bayes' theorem to deduce whether to shut down the production line.
- 🎮 **Viva Speed Quiz Blitz**: 60-second rapid-fire arcade with streak multipliers and audio synthesizer feedback.

### 6. 👔 Course Viva & Examiner Defense Simulator
- High-yield viva questions with:
  - **Examiner Intent:** What the examiner is testing.
  - **Model Response:** Concise, authoritative academic explanation.
  - **Mathematical Proof:** Step-by-step formula derivations.
  - **Examiner Trap & Defense:** Counter-questions and common candidate pitfalls (e.g., XOR non-linear separability, SVD vs Eigendecomposition numerical stability, Laplace smoothing).

---

## 💻 Technology Stack & Architecture
- **Frontend Architecture:** Pure HTML5 + Modern Vanilla CSS + Modern JavaScript (ES6+).
- **Zero External Dependencies:** No npm packages, node runtime, or bundlers needed to run locally.
- **Visual Rendering:** High-performance Canvas API with double buffering and responsive coordinate transforms.
- **Audio Synthesis:** Native Web Audio API procedural sound synthesizer (oscillator-generated chime, buzz, and victory chords without external media files).
- **Design System:** Deep dark glassmorphism theme (`#070d1a`), neon cyan/indigo/emerald accents, Inter & JetBrains Mono typography.

---

## 🚀 Running Locally

### Option 1: Direct Browser Launch (Simplest)
Simply double-click [`index.html`](./index.html) or open it directly in any modern browser:
```bash
# Windows PowerShell
Start-Process index.html
```

### Option 2: Local HTTP Server (Python / Node)
```bash
# Using Python
python -m http.server 8080

# Or using Node http-server
npx http-server -p 8080
```
Then visit `http://localhost:8080`.

---

## ☁️ Deployment

### Deployed to Vercel
This project is deployed on Vercel at production edge CDN:
- **Production URL:** [https://ktu-ai-learning-platform.vercel.app](https://ktu-ai-learning-platform.vercel.app)
- **GitHub Repository:** [https://github.com/Janeferdinant/ktu-ai-learning-platform](https://github.com/Janeferdinant/ktu-ai-learning-platform)

---

## 🏛️ Course Outcomes & Evaluation Scheme
- **Continuous Internal Evaluation (CIE):** 40 Marks
- **End Semester Examination (ESE):** 60 Marks (2.5 Hours)
- **Course Outcomes:**
  - **CO1:** Formulate search problems and develop neural network architectures.
  - **CO2:** Apply vector space principles, SVD, and PCA for dimensionality reduction.
  - **CO3:** Analyze probabilistic models and formulate Bayesian inference systems.
  - **CO4:** Evaluate machine learning classifiers, regression models, and clustering algorithms.

---

## 👩‍🏫 Author Attribution & Department
**Jane Rose N F**  
Assistant Professor, Department of Computer Science & Engineering (CSE)  
APJ Abdul Kalam Technological University (KTU), Kerala  
GitHub: [@Janeferdinant](https://github.com/Janeferdinant)
