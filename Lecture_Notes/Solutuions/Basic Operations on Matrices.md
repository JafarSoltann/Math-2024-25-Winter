## 1. Basic Operations on Matrices

For follwing matrices 

$$
\mathbf{A}=
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad
\mathbf{C}=
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
\qquad
\mathbf{D}=
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6 
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
1 & 2\\
4 & 5\\
7 & 8
\end{pmatrix}
$$

1. Calculate: $\mathbf{A}+\mathbf{B}$;  $\mathbf{B}-\mathbf{A}$;  $\mathbf{A}+\mathbf{C}$; $\mathbf{D}+\mathbf{E}$. 

2. Calculate $\frac{1}{2}\mathbf{A}$, $2\mathbf{B}$, $-3\mathbf{C}$, and $4\mathbf{D}$.

3. Calculate the products $\mathbf{A}\cdot \mathbf{B}$; $\mathbf{B} \cdot \mathbf{A}$; $\mathbf{A} \cdot \mathbf{D}$; $\mathbf{D} \cdot \mathbf{E}$.


### Solutions
### 1. Matrix Addition and Subtraction

#### $A + B$:
$$
A + B = \begin{pmatrix} 1+5 & 2+6 \\ 3+7 & 4+8 \end{pmatrix} = \begin{pmatrix} 6 & 8 \\ 10 & 12 \end{pmatrix}
$$

#### $B - A$:
$$
B - A = \begin{pmatrix} 5-1 & 6-2 \\ 7-3 & 8-4 \end{pmatrix} = \begin{pmatrix} 4 & 4 \\ 4 & 4 \end{pmatrix}
$$

#### $A + C$:
$$
A + C = \begin{pmatrix} 1+(-1) & 2+2 \\ 3+3 & 4+0 \end{pmatrix} = \begin{pmatrix} 0 & 4 \\ 6 & 4 \end{pmatrix}
$$

#### $D + E$:
$$
D + E = \begin{pmatrix} -1+1 & 2+2 & 3+4 \\ 4+5 & 0+7 & 6+8 \end{pmatrix} = \begin{pmatrix} 0 & 4 & 7 \\ 9 & 7 & 14 \end{pmatrix}
$$

---

### 2. Scalar Multiplication

#### $2A$:
$$
2A = 2 \times \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix} = \begin{pmatrix} 2 & 4 \\ 6 & 8 \end{pmatrix}
$$

#### $2B$:
$$
2B = 2 \times \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix} = \begin{pmatrix} 10 & 12 \\ 14 & 16 \end{pmatrix}
$$

#### $-3C$:
$$
-3C = -3 \times \begin{pmatrix} -1 & 2 \\ 3 & 0 \end{pmatrix} = \begin{pmatrix} 3 & -6 \\ -9 & 0 \end{pmatrix}
$$

#### $4D$:
$$
4D = 4 \times \begin{pmatrix} -1 & 2 & 3 \\ 4 & 0 & 6 \end{pmatrix} = \begin{pmatrix} -4 & 8 & 12 \\ 16 & 0 & 24 \end{pmatrix}
$$

---

### 3. Matrix Multiplication

#### $A \cdot B$:
$$
A \cdot B = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix} \cdot \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix} = \begin{pmatrix} 1(5) + 2(7) & 1(6) + 2(8) \\ 3(5) + 4(7) & 3(6) + 4(8) \end{pmatrix}
$$
$$
A \cdot B = \begin{pmatrix} 5 + 14 & 6 + 16 \\ 15 + 28 & 18 + 32 \end{pmatrix} = \begin{pmatrix} 19 & 22 \\ 43 & 50 \end{pmatrix}
$$

#### $B \cdot A$:
$$
B \cdot A = \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix} \cdot \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix} = \begin{pmatrix} 5(1) + 6(3) & 5(2) + 6(4) \\ 7(1) + 8(3) & 7(2) + 8(4) \end{pmatrix}
$$
$$
B \cdot A = \begin{pmatrix} 5 + 18 & 10 + 24 \\ 7 + 24 & 14 + 32 \end{pmatrix} = \begin{pmatrix} 23 & 34 \\ 31 & 46 \end{pmatrix}
$$

#### $A \cdot D$:
$$
A \cdot D = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix} \cdot \begin{pmatrix} -1 & 2 & 3 \\ 4 & 0 & 6 \end{pmatrix} = \begin{pmatrix} 1(-1) + 2(4) & 1(2) + 2(0) & 1(3) + 2(6) \\ 3(-1) + 4(4) & 3(2) + 4(0) & 3(3) + 4(6) \end{pmatrix}
$$
$$
A \cdot D = \begin{pmatrix} -1 + 8 & 2 + 0 & 3 + 12 \\ -3 + 16 & 6 + 0 & 9 + 24 \end{pmatrix} = \begin{pmatrix} 7 & 2 & 15 \\ 13 & 6 & 33 \end{pmatrix}
$$

#### $D \cdot E$:
$$
D \cdot E = \begin{pmatrix} -1 & 2 & 3 \\ 4 & 0 & 6 \end{pmatrix} \cdot \begin{pmatrix} 1 & 2 & 4 \\ 5 & 7 & 8 \end{pmatrix} = \begin{pmatrix} (-1)(1) + 2(5) + 3(0) & (-1)(2) + 2(7) + 3(0) & (-1)(4) + 2(8) + 3(0) \\ (4)(1) + (0)(5) + (6)(0) & (4)(2) + (0)(7) + (6)(0) & (4)(4) + (0)(8) + (6)(0) \end{pmatrix}
$$
$$
D \cdot E = \begin{pmatrix} -1 + 10 + 0 & -2 + 14 + 0 & -4 + 16 + 0 \\ 4 + 0 + 0 & 8 + 0 + 0 & 16 + 0 + 0 \end{pmatrix} = \begin{pmatrix} 9 & 12 & 12 \\ 4 & 8 & 16 \end{pmatrix}
$$

---

### Final Results:

- $A + B = \begin{pmatrix} 6 & 8 \\ 10 & 12 \end{pmatrix}$
- $B - A = \begin{pmatrix} 4 & 4 \\ 4 & 4 \end{pmatrix}$
- $A + C = \begin{pmatrix} 0 & 4 \\ 6 & 4 \end{pmatrix}$
- $D + E = \begin{pmatrix} 0 & 4 & 7 \\ 9 & 7 & 14 \end{pmatrix}$
- $2A = \begin{pmatrix} 2 & 4 \\ 6 & 8 \end{pmatrix}$
- $2B = \begin{pmatrix} 10 & 12 \\ 14 & 16 \end{pmatrix}$
- $-3C = \begin{pmatrix} 3 & -6 \\ -9 & 0 \end{pmatrix}$
- $4D = \begin{pmatrix} -4 & 8 & 12 \\ 16 & 0 & 24 \end{pmatrix}$
- $A \cdot B = \begin{pmatrix} 19 & 22 \\ 43 & 50 \end{pmatrix}$
- $B \cdot A = \begin{pmatrix} 23 & 34 \\ 31 & 46 \end{pmatrix}$
- $A \cdot D = \begin{pmatrix} 7 & 2 & 15 \\ 13 & 6 & 33 \end{pmatrix}$
- $D \cdot E = \begin{pmatrix} 9 & 12 & 12 \\ 4 & 8 & 16 \end{pmatrix}$
