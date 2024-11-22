## 4. Determinants from the Gauss Method and Triangular Matrices

Perform row and column operations to reduce the following matrices to an upper triangular form and calculate their determinants by taking the product of the diagonal elements.

$$
\mathbf{A} = \begin{pmatrix}
12 & 3 \\
-18 & -4
\end{pmatrix}\qquad\qquad
\mathbf{B} = \begin{pmatrix} 
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9 
\end{pmatrix}
$$

### Solutions

## Solution: Determinants from the Gauss Method and Triangular Matrices

We will perform row and column operations to reduce the matrices to an upper triangular form and calculate their determinants by taking the product of the diagonal elements.

### Matrix A:

$$
\mathbf{A} = \begin{pmatrix}
12 & 3 \\
-18 & -4
\end{pmatrix}
$$

1. **First, perform a row operation to eliminate the element below the pivot in the first column.**
   
   We add $\frac{3}{2}$ times the first row to the second row:
   $$
   R_2 \rightarrow R_2 + \frac{3}{2}R_1
   $$

   New second row:
   $$ 
   (-18) + \frac{3}{2} \times 12 = -18 + 18 = 0
   $$

   The matrix becomes:
   $$
   \mathbf{A} = \begin{pmatrix}
   12 & 3 \\
   0 & 5
   \end{pmatrix}
   $$

2. **The determinant of the matrix is the product of the diagonal elements:**

   $$
   \text{det}(\mathbf{A}) = 12 \times 5 = 60
   $$

---

### Matrix B:

$$
\mathbf{B} = \begin{pmatrix} 
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9 
\end{pmatrix}
$$

1. **First, perform a row operation to eliminate the element below the pivot in the first column.**
   
   Subtract 4 times the first row from the second row:
   $$
   R_2 \rightarrow R_2 - 4R_1
   $$

   New second row:
   $$
   (4 - 4 \times 1, 5 - 4 \times 2, 6 - 4 \times 3) = (0, -3, -6)
   $$

   Now, subtract 7 times the first row from the third row:
   $$
   R_3 \rightarrow R_3 - 7R_1
   $$

   New third row:
   $$
   (7 - 7 \times 1, 8 - 7 \times 2, 9 - 7 \times 3) = (0, -6, -12)
   $$

   The matrix becomes:
   $$
   \mathbf{B} = \begin{pmatrix} 
   1 & 2 & 3 \\
   0 & -3 & -6 \\
   0 & -6 & -12
   \end{pmatrix}
   $$

2. **Next, eliminate the element below the pivot in the second column by performing a row operation on the third row.**
   
   Add 2 times the second row to the third row:
   $$
   R_3 \rightarrow R_3 + 2R_2
   $$

   New third row:
   $$
   (0 + 2 \times 0, -6 + 2 \times (-3), -12 + 2 \times (-6)) = (0, 0, 0)
   $$

   The matrix becomes:
   $$
   \mathbf{B} = \begin{pmatrix} 
   1 & 2 & 3 \\
   0 & -3 & -6 \\
   0 & 0 & 0
   \end{pmatrix}
   $$

3. **The determinant of the matrix is the product of the diagonal elements:**

   $$
   \text{det}(\mathbf{B}) = 1 \times (-3) \times 0 = 0
   $$

---

### Final Answers:

- The determinant of $\mathbf{A}$ is $60$.
- The determinant of $\mathbf{B}$ is $0$.
