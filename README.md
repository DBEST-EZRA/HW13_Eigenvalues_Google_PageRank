# **Linear Algebra Assignment: Eigenvectors, Eigenvalues, and PageRank**

## **Overview**
This repository contains the solution for a linear algebra assignment involving the **QR decomposition**, **PageRank algorithm**, and the computation of **eigenvalues and eigenvectors** using the **QR algorithm**. The assignment is based on concepts from the course **CSCI 2033: Elementary Computational Linear Algebra** and involves Python programming and matrix computations.

### **Key Concepts Covered:**
- **QR Decomposition**: Breaking down a matrix into an orthogonal matrix \( Q \) and an upper triangular matrix \( R \).
- **PageRank Algorithm**: Calculating the importance vector of a graph using iterative matrix operations.
- **Eigenvalues and Eigenvectors**: Finding eigenvalues and eigenvectors using the QR algorithm.

## **Steps Involved:**
1. **Matrix Representation of Graph**:
   - Constructing an adjacency matrix for an undirected graph.
   - Normalizing the matrix columns to ensure each column sums to 1.

2. **Finding the Importance Vector**:
   - Using iterative matrix multiplication to compute the importance vector (similar to Google's PageRank algorithm).

3. **QR Algorithm for Eigenvalues**:
   - Implementing the QR algorithm to compute eigenvalues and eigenvectors of a matrix.
   - Verifying the results by comparing the computed eigenvalues and eigenvectors to those obtained using NumPy's `eig` function.

4. **Convergence and Verification**:
   - Checking the convergence of the iterative process using relative distance.
   - Verifying if the eigenvalue equation \( A v_0 = \lambda_0 v_0 \) holds.

## **File Structure:**
