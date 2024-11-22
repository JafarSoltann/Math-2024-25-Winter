## 6. Inverse of a Matrix using the Gauss Method

Find the inverse matrices using the Gauss method:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2\\
3 & 4
\end{pmatrix}
, \qquad
\mathbf{B} =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 1 \\
2 & 3 & 2
\end{pmatrix}
,\qquad
\mathbf{C} =
\begin{pmatrix}
0 & 0 & 1\\
0 & 1 & 0\\
1 & 0 & 0
\end{pmatrix}
$$

### Solutions

## 6. Inverse of a Matrix using the Gauss Method

We are given three matrices:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2\\
3 & 4
\end{pmatrix}, \qquad
\mathbf{B} =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 1 \\
2 & 3 & 2
\end{pmatrix}, \qquad
\mathbf{C} =
\begin{pmatrix}
0 & 0 & 1\\
0 & 1 & 0\\
1 & 0 & 0
\end{pmatrix}
$$

### 1. Finding the inverse of matrix $\mathbf{A}$

We will use the Gauss-Jordan elimination method to find the inverse of matrix $\mathbf{A}$.

#### Step 1: Set up the augmented matrix

The augmented matrix consists of the matrix $\mathbf{A}$ on the left and the identity matrix on the right:

$$
\left( \begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
3 & 4 & 0 & 1
\end{array} \right)
$$

#### Step 2: Perform row operations

We want to transform the left matrix into the identity matrix by performing row operations.

- First, subtract $3$ times row 1 from row 2:

$$
\left( \begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
0 & -2 & -3 & 1
\end{array} \right)
$$

- Next, multiply row 2 by $-1/2$:

$$
\left( \begin{array}{cc|cc}
1 & 2 & 1 & 0 \\
0 & 1 & 3/2 & -1/2
\end{array} \right)
$$

- Finally, subtract $2$ times row 2 from row 1:

$$
\left( \begin{array}{cc|cc}
1 & 0 & -2 & 1 \\
0 & 1 & 3/2 & -1/2
\end{array} \right)
$$

Thus, the inverse of $\mathbf{A}$ is:

$$
\mathbf{A}^{-1} =
\begin{pmatrix}
-2 & 1 \\
3/2 & -1/2
\end{pmatrix}
$$

### 2. Finding the inverse of matrix $\mathbf{B}$

The matrix $\mathbf{B}$ is a $3 \times 3$ matrix, and we will follow a similar approach.

#### Step 1: Set up the augmented matrix

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
4 & 5 & 1 & 0 & 1 & 0 \\
2 & 3 & 2 & 0 & 0 & 1
\end{array} \right)
$$

#### Step 2: Perform row operations

- Subtract $4$ times row 1 from row 2:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & -3 & -11 & -4 & 1 & 0 \\
2 & 3 & 2 & 0 & 0 & 1
\end{array} \right)
$$

- Subtract $2$ times row 1 from row 3:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & -3 & -11 & -4 & 1 & 0 \\
0 & -1 & -4 & -2 & 0 & 1
\end{array} \right)
$$

- Multiply row 2 by $-1/3$:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & 1 & 11/3 & 4/3 & -1/3 & 0 \\
0 & -1 & -4 & -2 & 0 & 1
\end{array} \right)
$$

- Add row 2 to row 3:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & 1 & 11/3 & 4/3 & -1/3 & 0 \\
0 & 0 & -1/3 & -2/3 & -1/3 & 1
\end{array} \right)
$$

- Multiply row 3 by $-3$:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & 1 & 11/3 & 4/3 & -1/3 & 0 \\
0 & 0 & 1 & 2 & 1 & -3
\end{array} \right)
$$

- Subtract $11/3$ times row 3 from row 2:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 3 & 1 & 0 & 0 \\
0 & 1 & 0 & -30/3 & 2/3 & 11 \\
0 & 0 & 1 & 2 & 1 & -3
\end{array} \right)
$$

- Subtract $3$ times row 3 from row 1:

$$
\left( \begin{array}{ccc|ccc}
1 & 2 & 0 & -5 & -3 & 9 \\
0 & 1 & 0 & -10 & 2 & 11 \\
0 & 0 & 1 & 2 & 1 & -3
\end{array} \right)
$$

Thus, the inverse of $\mathbf{B}$ is:

$$
\mathbf{B}^{-1} =
\begin{pmatrix}
-5 & -3 & 9 \\
-10 & 2 & 11 \\
2 & 1 & -3
\end{pmatrix}
$$

### 3. Finding the inverse of matrix $\mathbf{C}$

Matrix $\mathbf{C}$ is a permutation matrix, which is always invertible, and its inverse is its transpose.

The transpose of matrix $\mathbf{C}$ is:

$$
\mathbf{C}^{-1} =
\begin{pmatrix}
0 & 0 & 1\\
0 & 1 & 0\\
1 & 0 & 0
\end{pmatrix}
$$
