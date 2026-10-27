# APJ Abdul Kalam Technological University (KTU)
## AI & Data Science: Interactive Learning, Algorithm Labs & Viva Voce Platform
**Course Code:** GNEST305 • **Programme:** B.Tech (2024 Scheme) • **Credits:** 4 (L:T:P = 3:1:0:0)  
**Author:** Jane Rose (`Janeferdinant`), Assistant Professor, Dept. of Computer Science & Engineering  
**Live Deployment:** [https://ktu-ai-learning-platform.vercel.app](https://ktu-ai-learning-platform.vercel.app)  
**GitHub Repository:** [https://github.com/Janeferdinant/ktu-ai-learning-platform](https://github.com/Janeferdinant/ktu-ai-learning-platform)  

---

## 🌟 Executive Overview
This repository hosts a state-of-the-art, publication-grade academic web application tailored specifically for the **APJ Abdul Kalam Technological University (KTU)** Artificial Intelligence and Data Science curriculum.

Built to address both **conceptual algorithm intuition** and **rigorous oral viva examination defense**, the platform bridges abstract mathematical formulations with real-time visual canvases, gamified learning challenges, step-by-step solved quizzes, and faculty viva scenarios.

```
                              KTU AI & DS PORTAL (GNEST305)
                                            │
        ┌───────────────────┬───────────────┴───────────────┬───────────────────┐
        ▼                   ▼                               ▼                   ▼
┌───────────────┐   ┌───────────────┐               ┌───────────────┐   ┌───────────────┐
│  5 Algorithm  │   │   4 Concept   │               │ Solution Quiz │   │  Course Viva  │
│  Visual Labs  │   │ Mastery Games │               │     Arena     │   │ & Defense Hub │
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
- **Linear Perceptron Lab**: Real-time Cartesian coordinate space with live sliders for weights ($w_1, w_2$) and bias ($b$). Click to add data points (Left click: Class +1, Right click: Class -1). Features **1 Epoch Step** and **Auto-Converge** execution of Rosenblatt's learning rule.
- **K-Means Clustering & Voronoi Partitioner**: Dynamically tune $K$ (2 to 5), randomize data clusters, and step through the **Expectation-Maximization** cycle (Voronoi region assignment + centroid mean migration) with live Inertia (SSE) calculation.
- **SVD & PCA Projection Lab**: Correlated 2D data cloud with Principal Component eigenvectors ($v_1, v_2$) scaled by singular values $\sqrt{\lambda_1}, \sqrt{\lambda_2}$. Toggle projection to 1D subspace to inspect variance retained and reconstruction error.
- **Bayes Diagnostic Simulator**: Sliders for Prior $P(D)$, Sensitivity $P(+|D)$, and False Positive Rate $P(+|D^c)$ illustrating the **Base Rate Fallacy** and natural frequency breakdown across 10,000 components.
- **Gradient Descent Optimization Surface**: 2D quadratic cost surface $J(w_1, w_2)$ with adjustable learning rate $\eta$ and momentum $\beta$, showing convergence trajectories, oscillations, or divergence.

### 2. Gamified Concept Mastery Arena
- 🎮 **Hyperplane Slicer (Perceptron Boundary Arcade)**: 30-second countdown to rotate and shift the decision boundary to achieve 100% linear classification before time expires.
- 🎮 **Eigen-Hunter (Invariance Quest)**: Rotate test vector $v$ on the unit circle until transformed vector $Av$ is collinear with $v$, capturing the invariant **Eigenvector** and its **Eigenvalue $\lambda$**.
- 🎮 **Bayes Detective (Industrial Diagnostics Mystery)**: Solve a real-world CNC bearing vibration alarm using Bayes' theorem to deduce whether to shut down the production line.
- 🎮 **Viva Speed Quiz Blitz**: 60-second rapid-fire arcade with streak multipliers and audio synthesizer feedback.

### 3. Solution Quiz Arena (With Step-by-Step Derivations)
- Comprehensive multi-module quiz bank featuring conceptual and numerical calculation problems.
- Instant feedback with **complete mathematical derivations**, formula steps, and option-by-option rationale.

### 4. Course Viva & Examiner Defense Simulator
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
This project is configured for instantaneous deployment on Vercel:
```bash
# Deploy to Vercel via CLI
npx vercel --prod
```
Static files (`index.html`, `README.md`) are served directly at the root edge CDN with global caching and sub-100ms latency.

---

## 📜 Evaluation & Course Outcomes
- **Continuous Internal Evaluation (CIE):** 40 Marks
- **End Semester Examination (ESE):** 60 Marks (2.5 Hours)
- **Course Outcomes:**
  - **CO1:** Formulate search problems and develop neural network architectures.
  - **CO2:** Apply vector space principles, SVD, and PCA for dimensionality reduction.
  - **CO3:** Analyze probabilistic models and formulate Bayesian inference systems.
  - **CO4:** Evaluate machine learning classifiers, regression models, and clustering algorithms.

---

## 📄 License
Academic & Educational Use Only • APJ Abdul Kalam Technological University (KTU).
Developed by **Jane Rose** (`Janeferdinant`).
