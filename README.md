# Dimensionality-Reduction-via-Spectral-Decomposition

🚀 Project Overview
This project implements Principal Component Analysis (PCA) from scratch using Python to analyze the 4-dimensional Iris Dataset. The goal is to demonstrate how the Spectral Theorem and Eigen-decomposition can be used to compress data while preserving its most critical information.

🧠 Mathematical Logic
As per the fundamental principles of Linear Algebra:
- Direction of Maximum Variance: The largest eigenvector of the covariance matrix always points in the direction of the largest variance (spread) of the data.
- Orthogonality: The 2nd largest eigenvector is always orthogonal to the largest and points in the direction of the 2nd largest spread.
- Optimization: In PCA, we find the coordinate axes where variance is maximum, allowing us to discard the "Null Space" (noise) of the transformation.

🛠️ Implementation
The implementation follows these steps:
1. Standardization: Centering the 4D data at the origin of the vector space.
2. Covariance Calculation: Constructing a symmetric, positive semi-definite matrix.
3. Spectral Decomposition: Computing eigenvalues (λ) and eigenvectors (v) .
4. Projection: Reducing the 4D input to 2D and 3D subspaces for visualization.

📊 Results
1. 2D Projection: Captured ~95.8% of the total dataset variance.

2. 3D Projection: Captured ~99.4% of the total dataset variance.

Conclusion: This method allows for significant data compression (reducing storage by 50-75%) while maintaining the structural integrity required for machine learning models.

