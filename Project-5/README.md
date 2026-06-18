# Calculative Foundation Practical Project

## Overview

This project demonstrates the implementation of fundamental concepts of Linear Algebra, Matrix Operations, Dimensionality Reduction, and Machine Learning using Python. The project uses a student performance dataset containing 100 records and applies various mathematical and analytical techniques to understand data representation, transformations, and classification.

---

## Dataset Information

* Dataset Size: 100 Records
* Features: 5 Numerical Subject Scores
* Shape: (100, 6)
* Environment: Jupyter Notebook
* Language: Python

---

## Technologies Used

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn

---

## Tasks Performed

### 1. Vector Representation

* Converted student score records into vectors.
* Displayed vectors for selected students.
* Analyzed score representation in vector form.

### 2. Vector Operations

Performed:

* L1 Norm
* L2 Norm
* Dot Product
* Angle Between Vectors
* Cross Product

These operations help understand vector magnitude, similarity, and orientation.

---

### 3. Vector Projection

* Projected one student vector onto another.
* Calculated projection values mathematically.

---

### 4. Matrix Operations

Performed:

* Matrix Creation
* Matrix Transpose
* Covariance Matrix
* Determinant Calculation
* Matrix Inversion

These operations form the foundation of many machine learning algorithms.

---

### 5. Linear Transformation

Applied:

* Rotation Transformation
* Scaling Transformation

Used to demonstrate how data changes under geometric transformations.

---

### 6. Eigenvalues and Eigenvectors

* Computed eigenvalues.
* Computed eigenvectors.
* Analyzed principal directions of data variance.

---

### 7. LU Decomposition

Decomposed matrices into:

* P Matrix
* L Matrix
* U Matrix

Useful for solving systems of linear equations efficiently.

---

### 8. Singular Value Decomposition (SVD)

Performed SVD and extracted:

* Singular Values
* Left Singular Vectors
* Right Singular Vectors

SVD is widely used in dimensionality reduction and data compression.

---

### 9. Principal Component Analysis (PCA)

Implemented PCA for dimensionality reduction.

Key Results:

* Reduced data to 2 principal components.
* Explained Variance Ratio:

  * PC1 = 25.71%
  * PC2 = 24.68%

Generated a PCA scatter plot for visualization of all 100 students.

---

### 10. Linear Discriminant Analysis (LDA)

Performed classification based on student performance.

Steps:

* Calculated overall mean score.
* Classified students as:

  * Above Average
  * Below Average
* Split data into training and testing sets.
* Trained LDA classifier.
* Evaluated model performance.

Metrics Generated:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Results

### PCA

* Successfully projected 100 students into a two-dimensional space.
* Visualized principal components through scatter plots.

### LDA

* Successfully classified students into performance categories.
* Generated confusion matrix and classification report.
* Evaluated classification accuracy.

### Mathematical Analysis

Successfully implemented:

* Vector Operations
* Matrix Operations
* Linear Transformations
* Eigen Decomposition
* LU Decomposition
* Singular Value Decomposition
* PCA
* LDA

---

## Learning Outcomes

Through this project, the following concepts were understood and implemented:

* Vector Mathematics
* Matrix Algebra
* Linear Transformations
* Eigenvalues & Eigenvectors
* Matrix Factorization Techniques
* Dimensionality Reduction
* Statistical Data Analysis
* Machine Learning Classification
* Data Visualization

---

## Conclusion

This project successfully demonstrates the practical implementation of core Calculative Foundation concepts using Python. Mathematical operations, matrix decompositions, PCA, and LDA were applied to real student performance data, providing both theoretical understanding and practical machine learning experience.

The notebook is fully executable and suitable for academic submission.
