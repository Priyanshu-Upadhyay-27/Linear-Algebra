# Linear Algebra and Dimensionality Reduction with PCA

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This repository contains a complete, from-scratch and library-based implementation of **Principal Component Analysis (PCA)**. Developed as part of a college practical assessment, this project demonstrates the mathematical foundations of dimensionality reduction.

The core objective is to reduce the feature space while retaining the maximum possible variance, allowing for more efficient downstream machine learning pipelines.

## 🏆 Certification & Validation
This practical implementation is backed by formal study. 
* **Course/Specialization:** Mathematics for Machine Learning
* **Issuing Authority:** Coursera / DeepLearning.AI
* **Credential:** [Link to verified certificate here]

*(See the attached practical report for the physical copy of the certification).*

## 🧠 Technical Concepts Covered
1. **Data Preprocessing:** Standardizing features (Z-score normalization) to ensure PCA is not skewed by variable scale.
2. **Covariance Matrix Calculation:** Understanding feature relationships.
3. **Eigendecomposition:** Extracting Eigenvectors (principal axes) and Eigenvalues (magnitude of variance).
4. **Explained Variance:** Utilizing the "Elbow Method" via cumulative explained variance to select the optimal $k$ components.
5. **Data Projection:** Transforming the original high-dimensional data into the new lower-dimensional subspace.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`

## 📂 Repository Structure
```text
/
├── .gitignore
├── README.md
├── C1_W4_Lab_1_Interpreting_eigenvalues_and_eigenvectors.ipynb
├── C1W2_UGL_solving_linear_systems_2_variables.ipynb
├── C1W2_UGL_solving_linear_systems_3_variables.ipynb
├── C1W3_Assignment.ipynb
├── C1W3_UGL_2_matrix_multiplication.ipynb
├── C1W3_UGL_3_linear_transformations.ipynb
├── C1W4_Assignment.ipynb
├── Linear Algebra.ipynb
├── Linear Equation Solver from Scratch.ipynb
└── Numpy.ipynb
```

## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/Priyanshu-Upadhyay-27/Linear-Algebra.git](https://github.com/Priyanshu-Upadhyay-27/Linear-Algebra.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd Linear-Algebra
   ```
3. Install the required dependencies:
   ```bash
   pip install numpy pandas scikit-learn
   ```
4. Launch the Jupyter Notebook to view the analysis:
   ```bash
   jupyter notebook notebooks/PCA_Implementation_and_Analysis.ipynb
   ```

## ⚖️ Disclaimer & Academic Integrity
This repository contains a practical implementation created for academic purposes. Portions of the foundational code or dataset may be based on educational materials provided by the Mathematics for Machine Learning course. 

This repository is intended to serve as a personal portfolio piece and proof of concept. The code is provided as-is without a formal open-source license. Please respect the intellectual property of the original course creators regarding the reuse of their lab materials.

---
**Author:** Priyanshu Upadhyay  
*Computer Science and Engineering Undergraduate | KIET Group of Institutions*