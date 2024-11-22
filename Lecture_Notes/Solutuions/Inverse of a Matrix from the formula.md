## 5. Inverse of a Matrix from the formula

1. Find the inverse matrix for matrix 

$$\mathbf{A}=\begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}$$

and verify if the result is correct.

2. Determine the rank of the matrix:

$$\mathbf{B} =
\begin{pmatrix}
4 & -3 & 7 \\
-1 & 6 & 3 \\
2 & 9 & 1
\end{pmatrix}$$

### Solutions

## Solution

### 1. Inverse of Matrix A

Given matrix:

$$
\mathbf{A} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$

#### Step 1: Find the determinant of matrix A

The determinant of a $3 \times 3$ matrix is given by the formula:

$$
\text{det}(\mathbf{A}) = a(ei - fh) - b(di - fg) + c(dh - eg)
$$

For matrix $\mathbf{A}$:

$$
\mathbf{A} = \begin{pmatrix}
a & b & c \\
d & e & f \\
g & h & i
\end{pmatrix} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$

Substituting the values:

$$
\text{det}(\mathbf{A}) = 2 \left( (1)(0) - (0)(2) \right) - 0 \left( (0)(0) - (0)(1) \right) + 1 \left( (0)(2) - (1)(1) \right)
$$

$$
\text{det}(\mathbf{A}) = 2(0 - 0) - 0(0 - 0) + 1(0 - 1) = 0 + 0 - 1 = -1
$$

#### Step 2: Find the inverse of matrix A

The inverse of a $3 \times 3$ matrix is given by:

$$
\mathbf{A}^{-1} = \frac{1}{\text{det}(\mathbf{A})} \cdot \text{adj}(\mathbf{A})
$$

Since the determinant is $-1$, we need to find the adjugate matrix of $\mathbf{A}$.

The adjugate matrix is the transpose of the cofactor matrix. The cofactor matrix is calculated by taking the determinant of $2 \times 2$ submatrices for each element.

Cofactors for $\mathbf{A}$ are calculated as follows:

- $C_{11} = \text{det}\begin{pmatrix} 1 & 0 \\ 2 & 0 \end{pmatrix} = (1)(0) - (0)(2) = 0$
- $C_{12} = -\text{det}\begin{pmatrix} 0 & 0 \\ 1 & 0 \end{pmatrix} = -(0 - 0) = 0$
- $C_{13} = \text{det}\begin{pmatrix} 0 & 1 \\ 1 & 2 \end{pmatrix} = (0)(2) - (1)(1) = -1$
- $C_{21} = -\text{det}\begin{pmatrix} 0 & 1 \\ 2 & 0 \end{pmatrix} = -(0 - 2) = 2$
- $C_{22} = \text{det}\begin{pmatrix} 2 & 1 \\ 1 & 0 \end{pmatrix} = (2)(0) - (1)(1) = -1$
- $C_{23} = -\text{det}\begin{pmatrix} 2 & 0 \\ 1 & 2 \end{pmatrix} = -(4 - 0) = -4$
- $C_{31} = \text{det}\begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix} = (0)(0) - (1)(1) = -1$
- $C_{32} = -\text{det}\begin{pmatrix} 2 & 1 \\ 0 & 0 \end{pmatrix} = -(0 - 0) = 0$
- $C_{33} = \text{det}\begin{pmatrix} 2 & 0 \\ 0 & 1 \end{pmatrix} = (2)(1) - (0)(0) = 2$

Thus, the cofactor matrix is:

$$
\text{Cofactor}(\mathbf{A}) = \begin{pmatrix}
0 & 0 & -1 \\
2 & -1 & -4 \\
-1 & 0 & 2
\end{pmatrix}
$$

The adjugate matrix is the transpose of the cofactor matrix:

$$
\text{adj}(\mathbf{A}) = \begin{pmatrix}
0 & 2 & -1 \\
0 & -1 & 0 \\
-1 & -4 & 2
\end{pmatrix}
$$

Now, compute the inverse:

$$
\mathbf{A}^{-1} = \frac{1}{-1} \cdot \begin{pmatrix}
0 & 2 & -1 \\
0 & -1 & 0 \\
-1 & -4 & 2
\end{pmatrix} = \begin{pmatrix}
0 & -2 & 1 \\
0 & 1 & 0 \\
1 & 4 & -2
\end{pmatrix}
$$

#### Step 3: Verify the result

To verify, we multiply $\mathbf{A}$ and $\mathbf{A}^{-1}$:

$$
\mathbf{A} \cdot \mathbf{A}^{-1} = \begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix} \cdot \begin{pmatrix}
0 & -2 & 1 \\
0 & 1 & 0 \\
1 & 4 & -2
\end{pmatrix}
$$

Performing the matrix multiplication:

$$
= \begin{pmatrix}
(2)(0) + (0)(0) + (1)(1) & (2)(-2) + (0)(1) + (1)(4) & (2)(1) + (0)(0) + (1)(-2) \\
(0)(0) + (1)(0) + (0)(1) & (0)(-2) + (1)(1) + (0)(4) & (0)(1) + (1)(0) + (0)(-2) \\
(1)(0) + (2)(0) + (0)(1) & (1)(-2) + (2)(1) + (0)(4) & (1)(1) + (2)(0) + (0)(-2)
\end{pmatrix}
$$

$$
= \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
$$

Thus, $\mathbf{A} \cdot \mathbf{A}^{-1} = \mathbf{I}$, confirming the inverse is correct.

### 2. Rank of Matrix B

Given matrix:

$$
\mathbf{B} = \begin{pmatrix}
4 & -3 & 7 \\
-1 & 6 & 3 \\
2 & 9 & 1
\end{pmatrix}
$$

#### Step 1: Perform row reduction

We can apply Gaussian elimination to find the rank.

1. First, swap rows 1 and 2 to simplify calculations:

$$
\mathbf{B} = \begin{pmatrix}
-1 & 6 & 3 \\
4 & -3 & 7 \\
2 & 9 & 1
\end{pmatrix}
$$

2. Add $4$ times the first row to the second row:

$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 21 & 31 \\
2 & 9 & 1
\end{pmatrix}
$$

3. Subtract $2$ times the first row from the third row:

$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 21 & 31 \\
0 & -3 & -5
\end{pmatrix}
$$

4. Multiply the second row by $\frac{1}{21}$:

$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 1 & \frac{31}{21} \\
0 & -3 & -5
\end{pmatrix}
$$

5. Add $3$ times the second row to the third row:

$$
\begin{pmatrix}
-1 & 6 & 3 \\
0 & 1 & \frac{31}{21} \\
0 & 0 & \frac{2}{7}
\end{pmatrix}
$$

At this point, we have three non-zero rows, so the rank of matrix $\mathbf{B}$ is 3.

Thus, the rank of $\mathbf{B}$ is 3.
