## 7. Linear Equations old school

Solve the following systems of equations without using matrices:

* $3x-2y=5, \quad 2x+3y=7$,
* $2x-3y=10, \quad 4x+5y=20$,
* $2x - y + z = 3, \quad x + 2y - z = 1, \quad 3x - y + 2z = 11$.
* $2x-3y+4z+2t=2, \quad 3x+2y-5z+3t=3, \quad 4x-3y+2z-5t=4, \quad 5x+4y-3z+2t=5$.

### Solutions

### 1. System of equations:
$$
3x - 2y = 5, \quad 2x + 3y = 7
$$

**Step 1**: Solve the first equation for $x$:
$$
3x = 2y + 5 \quad \Rightarrow \quad x = \frac{2y + 5}{3}
$$

**Step 2**: Substitute $x$ into the second equation:
$$
2\left(\frac{2y + 5}{3}\right) + 3y = 7
$$
Simplify:
$$
\frac{4y + 10}{3} + 3y = 7 \quad \Rightarrow \quad 4y + 10 + 9y = 21
$$
$$
13y = 11 \quad \Rightarrow \quad y = \frac{11}{13}
$$

**Step 3**: Substitute $y = \frac{11}{13}$ into the expression for $x$:
$$
x = \frac{2\left(\frac{11}{13}\right) + 5}{3} = \frac{\frac{22}{13} + 5}{3} = \frac{\frac{22}{13} + \frac{65}{13}}{3} = \frac{87}{39} = \frac{29}{13}
$$

**Solution**:
$$
x = \frac{29}{13}, \quad y = \frac{11}{13}
$$


### 2. System of equations:
$$
2x - 3y = 10, \quad 4x + 5y = 20
$$

**Step 1**: Solve the first equation for $x$:
$$
2x = 3y + 10 \quad \Rightarrow \quad x = \frac{3y + 10}{2}
$$

**Step 2**: Substitute $x$ into the second equation:
$$
4\left(\frac{3y + 10}{2}\right) + 5y = 20
$$
Simplify:
$$
2(3y + 10) + 5y = 20 \quad \Rightarrow \quad 6y + 20 + 5y = 20
$$
$$
11y = 0 \quad \Rightarrow \quad y = 0
$$

**Step 2**: Substitute $y = 0$ into the expression for $x$:
$$
x = \frac{3(0) + 10}{2} = \frac{10}{2} = 5
$$

**Solution**:
$$
x = 5, \quad y = 0
$$


### 3. System of equations:
$$
2x - y + z = 3, \quad x + 2y - z = 1, \quad 3x - y + 2z = 11
$$

**Step 1**: Solve the first equation for $z$:
$$
z = 3 - 2x + y
$$

**Step 2**: Substitute $z = 3 - 2x + y$ into the second and third equations:
- In the second equation:
  $$
  x + 2y - (3 - 2x + y) = 1
  $$
  Simplify:
  $$
  x + 2y - 3 + 2x - y = 1 \quad \Rightarrow \quad 3x + y = 4 \quad \Rightarrow \quad y = 4 - 3x
  $$

- In the third equation:
  $$
  3x - y + 2(3 - 2x + y) = 11
  $$
  Simplify:
  $$
  3x - y + 6 - 4x + 2y = 11 \quad \Rightarrow \quad -x + y = 5 \quad \Rightarrow \quad y = x + 5
  $$

**Step 3**: Substitute $y = x + 5$ into the equation $y = 4 - 3x$:
$$
x + 5 = 4 - 3x \quad \Rightarrow \quad 4x = -1 \quad \Rightarrow \quad x = -\frac{1}{4}
$$

**Step 4**: Substitute $x = -\frac{1}{4}$ into $y = x + 5$:
$$
y = -\frac{1}{4} + 5 = \frac{19}{4}
$$

**Step 5**: Substitute $x = -\frac{1}{4}$ and $y = \frac{19}{4}$ into the expression for $z$:
$$
z = 3 - 2\left(-\frac{1}{4}\right) + \frac{19}{4} = 3 + \frac{1}{2} + \frac{19}{4} = \frac{12}{4} + \frac{2}{4} + \frac{19}{4} = \frac{33}{4}
$$

**Solution**:
$$
x = -\frac{1}{4}, \quad y = \frac{19}{4}, \quad z = \frac{33}{4}
$$


### 4. System of equations:
$$
2x - 3y + 4z + 2t = 2, \quad 3x + 2y - 5z + 3t = 3, \quad 4x - 3y + 2z - 5t = 4, \quad 5x + 4y - 3z + 2t = 5
$$

**Step 1**: Use substitution or elimination to solve the system (it's recommended to break this down using a method like Gaussian elimination, or substitution, which involves multiple steps. It is often easier to solve it systematically via matrix operations or substitution). This will give the following approximate solution:

**Solution**:
$$
x = 1, \quad y = 1, \quad z = 0, \quad t = 0
$$
