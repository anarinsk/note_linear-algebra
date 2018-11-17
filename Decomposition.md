# Where 

https://pdfs.semanticscholar.org/1f79/700e56f0624198282aaac894c8d9ba27da10.pdf

# LU, LDU 

- application: square 
- solving for $n \times n$ linear system

# Cholesky 

- [source](https://en.wikipedia.org/wiki/Cholesky_decomposition)
- application: square, hermitian, positive-definite 
- hermitian: $a_{ij} = \overline{a_{ji}}$, $A = \overline{A^T}$. If A is real, A is symmetric. 
- $A=LL^*$
	- $L$ is lower triangular matrix with real and positive diagonal entries. 
	- $L^*$ is conjugated transpose.

# Eigendecomposition (spectral decomposition)  
  
  - [source]()
  - application: square matrix $A$ with linearly independent eigenvectors (not necessarily distinct eigenvalues)
  - $A = V D V^{-1}$,  $AV = VD$
  $A[v_1, v_2] = [v_1, v_2]
  \left( \begin{matrix}
   \lambda_1 & 0 \\
   0 & \lambda_2 \\
   \end{matrix}\right)$
  $A v_1 = \lambda_1 v_1$
  - more application:  For any real  symmetric
  $A = V D V^T$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0Njc5Mzg0MzRdfQ==
-->