## 22. Extremum
### 6. Maximizing Profit Function P(u)
The profit function is $P(u) = -2u^2 + 50u - 300$, where $u$ is the number of units sold. Find the number of units that maximize profit.
![alt text](image.png)

The profit function is  $P(u) = -2u^2 + 50u - 300$.

#### Step 1: Differentiate P(u):
$$
P'(u) = -4u + 50
$$

#### Step 2: Find the critical points:
Set P'(u) = 0 :
$-4u + 50 = 0 \quad \implies \quad u = \frac{50}{4} = 12.5$

#### Step 3: Verify maximum:
The second derivative is:
$P''(u) = -4$
Since P''(u) < 0, the function has a **maximum** at u = 12.5

#### Final Answer:
The profit is maximized when $\mathbf{u = 12.5}$ units are sold.

---

### 7. Largest Rectangle Enclosed by 10m String
 You have 10 meters of string, and you need to use it to enclose the largest possible rectangular. Find the dimensions of the rectangle.
 ![alt text](image-1.png)

The string forms the **perimeter** of the rectangle. Let the dimensions of the rectangle be x (length) and y (width).

#### Step 1: Perimeter equation:
$2x + 2y = 10 \quad \implies \quad x + y = 5 \quad \implies \quad y = 5 - x$

#### Step 2: Area of the rectangle:
$A = x \cdot y = x(5 - x) = 5x - x^2$

#### Step 3: Differentiate A(x):
$A'(x) = 5 - 2x$

#### Step 4: Find the critical points:
Set  A'(x) = 0 :
$5 - 2x = 0 \quad \implies \quad x = \frac{5}{2} = 2.5$

#### Step 5: Verify maximum:
The second derivative is:
$A''(x) = -2$
Since $A''(x) < 0$, the function has a **maximum** at x = 2.5

#### Final Answer:
The dimensions of the rectangle are $\mathbf{x = 2.5 \, m}$ and $\mathbf{y = 2.5 \, m}$ (a square).

---

### 8. Extremum of $f(x) = x^2 + 3x - 5$
Find extremum od $f(x) = x^2 + 3x - 5$.
![alt text](image-2.png)

#### Step 1: Differentiate f(x):
$f'(x) = 2x + 3$

#### Step 2: Find critical points:
Set $f'(x) = 0$:
$2x + 3 = 0 \quad \implies \quad x = -\frac{3}{2}$

#### Step 3: Verify minimum:
The second derivative is:
$f''(x) = 2$
Since $f''(x) > 0$, the function has a **minimum** at $x = -\frac{3}{2}$.

#### Final Answer:
The minimum value of \(f(x)\) is:
$f\left(-\frac{3}{2}\right) = \left(-\frac{3}{2}\right)^2 + 3\left(-\frac{3}{2}\right) - 5 = \frac{9}{4} - \frac{9}{2} - 5 = -\frac{29}{4}$

The minimum occurs at $\mathbf{x = -\frac{3}{2}}$, with $\mathbf{f(x) = -\frac{29}{4}}$.

---

### 9. Extremum of $f(x) = \frac{x^2 + 2x + 1}{x - 1}$
 Find extremum of $f(x) =\frac{x^2+2x+1}{x-1}$.
 ![alt text](image-3.png)

#### Step 1: Simplify f(x):
Factor the numerator:
$f(x) = \frac{(x + 1)^2}{x - 1}$

#### Step 2: Differentiate f(x) using the quotient rule:
$f'(x) = \frac{(x - 1) \cdot 2(x + 1) - (x + 1)^2 \cdot 1}{(x - 1)^2}$
Simplify the numerator:
$f'(x) = \frac{2(x + 1)(x - 1) - (x + 1)^2}{(x - 1)^2} = \frac{2x^2 - 2 - x^2 - 2x - 1}{(x - 1)^2}$
$f'(x) = \frac{x^2 - 2x - 3}{(x - 1)^2}$

#### Step 3: Find critical points:
Set $f'(x) = 0$:
$x^2 - 2x - 3 = 0 \quad \implies \quad (x - 3)(x + 1) = 0$
$x = 3 \quad \text{or} \quad x = -1$

#### Step 4: Verify extremum:
For x = 3 and x = -1, check the second derivative or test intervals to confirm maximum or minimum. Exclude x = 1 because it causes division by zero.

#### Final Answer:
The critical points are $\mathbf{x = 3}$ and $\mathbf{x = -1}$. Substitute these into $f(x)$ to find the corresponding extremum values:
$f(3) = \frac{(3 + 1)^2}{3 - 1} = \frac{16}{2} = 8, \quad f(-1) = \frac{(-1 + 1)^2}{-1 - 1} = 0$

Extremum values are f(3) = 8 (maximum) and f(-1) = 0 (minimum).

## 23. Taylor Series
1. Find the Taylor series and visualize obtained functions in Geogebra:
- $f(x) = \cos(x)$ around $x = 0$ up to the 4th degree.

### Taylor Series of $f(x) = \cos(x)$ around $x = 0$ up to the 4th degree

To find the Taylor series of $f(x) = \cos(x)$ around $x = 0$ up to the 4th degree, follow these steps:

#### 1. Find the derivatives of $f(x) = \cos(x)$:
- $f(x) = \cos(x)$
- $f'(x) = -\sin(x)$
- $f''(x) = -\cos(x)$
- $f^{(3)}(x) = \sin(x)$
- $f^{(4)}(x) = \cos(x)$

#### 2. Evaluate the derivatives at $x = 0$:
- $f(0) = \cos(0) = 1$
- $f'(0) = -\sin(0) = 0$
- $f''(0) = -\cos(0) = -1$
- $f^{(3)}(0) = \sin(0) = 0$
- $f^{(4)}(0) = \cos(0) = 1$

#### 3. Write the Taylor series formula:
The Taylor series around $x = 0$ is given by:
$f(x) = f(0) + f'(0) \frac{x}{1!} + f''(0) \frac{x^2}{2!} + f^{(3)}(0) \frac{x^3}{3!} + f^{(4)}(0) \frac{x^4}{4!} + \cdots$

#### 4. Substitute the values into the series:
Substitute the derivatives evaluated at $x = 0$ into the formula:
$f(x) = 1 + 0 \cdot \frac{x}{1!} - 1 \cdot \frac{x^2}{2!} + 0 \cdot \frac{x^3}{3!} + 1 \cdot \frac{x^4}{4!}.$

Simplify:
$f(x) = 1 - \frac{x^2}{2} + \frac{x^4}{24}.$

#### Conclusion:
The Taylor series of $ \cos(x) $ around $ x = 0 $ up to the 4th degree is:
$\cos(x) \approx 1 - \frac{x^2}{2} + \frac{x^4}{24}.$

![alt text](image-4.png)
https://www.geogebra.org/calculator/qtjafubg
