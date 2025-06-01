# LaTeX Formulas in Collapsible Sections

## Basic Mathematical Formulas

<details>
<summary>📐 Fundamental Theorems</summary>

### Pythagorean Theorem
For a right triangle with legs of length $$a$$ and $$b$$, and hypotenuse of length $$c$$:

$$a^2 + b^2 = c^2$$

### Quadratic Formula
For the equation $$ax^2 + bx + c = 0$$, the solutions are:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

### Euler's Identity
Often called the most beautiful equation in mathematics:

$$e^{i\pi} + 1 = 0$$

</details>

## Calculus Formulas

<details>
<summary>🔢 Derivatives and Integrals</summary>

### Common Derivatives

| Function | Derivative |
|----------|------------|
| $$f(x) = x^n$$ | $$f'(x) = nx^{n-1}$$ |
| $$f(x) = e^x$$ | $$f'(x) = e^x$$ |
| $$f(x) = \ln(x)$$ | $$f'(x) = \frac{1}{x}$$ |
| $$f(x) = \sin(x)$$ | $$f'(x) = \cos(x)$$ |
| $$f(x) = \cos(x)$$ | $$f'(x) = -\sin(x)$$ |

### Fundamental Theorem of Calculus
If $$F(x) = \int_a^x f(t) \, dt$$, then:

$$F'(x) = f(x)$$

And:

$$\int_a^b f(x) \, dx = F(b) - F(a)$$

### Integration by Parts
$$\int u \, dv = uv - \int v \, du$$

</details>

## Linear Algebra

<details>
<summary>🔢 Matrices and Vectors</summary>

### Matrix Multiplication
For matrices $$A_{m \times n}$$ and $$B_{n \times p}$$, the product $$C = AB$$ is:

$$C_{ij} = \sum_{k=1}^{n} A_{ik}B_{kj}$$

### Determinant of a 2×2 Matrix
For matrix $$A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$:

$$\det(A) = ad - bc$$

### Eigenvalue Equation
For a square matrix $$A$$ with eigenvalue $$\lambda$$ and eigenvector $$\mathbf{v}$$:

$$A\mathbf{v} = \lambda\mathbf{v}$$

### Vector Cross Product
For vectors $$\mathbf{a} = (a_1, a_2, a_3)$$ and $$\mathbf{b} = (b_1, b_2, b_3)$$:

$$\mathbf{a} \times \mathbf{b} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}$$

</details>

## Statistics and Probability

<details>
<summary>📊 Statistical Formulas</summary>

### Normal Distribution
The probability density function of a normal distribution with mean $$\mu$$ and standard deviation $$\sigma$$:

$$f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2}$$

### Bayes' Theorem
$$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$$

### Sample Variance
For a sample $$x_1, x_2, \ldots, x_n$$ with sample mean $$\bar{x}$$:

$$s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2$$

### Central Limit Theorem
For a sample of size $$n$$ from a population with mean $$\mu$$ and standard deviation $$\sigma$$:

$$\bar{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right)$$ as $$n \to \infty$$

</details>

## Complex Mathematical Proofs

<details>
<summary>🧮 Advanced Proofs</summary>

### Proof: $$\sqrt{2}$$ is Irrational

**Theorem:** $$\sqrt{2}$$ is irrational.

**Proof by contradiction:**

Assume $$\sqrt{2}$$ is rational. Then $$\sqrt{2} = \frac{p}{q}$$ where $$p, q \in \mathbb{Z}$$, $$q \neq 0$$, and $$\gcd(p,q) = 1$$.

Squaring both sides: $$2 = \frac{p^2}{q^2}$$

Therefore: $$2q^2 = p^2$$

This means $$p^2$$ is even, so $$p$$ must be even. Let $$p = 2k$$ for some integer $$k$$.

Substituting: $$2q^2 = (2k)^2 = 4k^2$$

Simplifying: $$q^2 = 2k^2$$

This means $$q^2$$ is even, so $$q$$ must be even.

But if both $$p$$ and $$q$$ are even, then $$\gcd(p,q) \geq 2$$, contradicting our assumption that $$\gcd(p,q) = 1$$.

Therefore, $$\sqrt{2}$$ is irrational. $$\square$$

### L'Hôpital's Rule

If $$\lim_{x \to a} f(x) = \lim_{x \to a} g(x) = 0$$ or $$\pm\infty$$, and $$g'(x) \neq 0$$ near $$a$$, then:

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}$$

provided the limit on the right exists.

</details>

## Physics Formulas

<details>
<summary>⚛️ Physics Equations</summary>

### Classical Mechanics

**Newton's Second Law:**
$$\mathbf{F} = m\mathbf{a} = m\frac{d\mathbf{v}}{dt} = m\frac{d^2\mathbf{r}}{dt^2}$$

**Kinetic Energy:**
$$KE = \frac{1}{2}mv^2$$

**Gravitational Force:**
$$F = G\frac{m_1 m_2}{r^2}$$

### Electromagnetism

**Coulomb's Law:**
$$\mathbf{F} = k_e \frac{q_1 q_2}{r^2} \hat{\mathbf{r}}$$

**Maxwell's Equations:**
$$\nabla \cdot \mathbf{E} = \frac{\rho}{\epsilon_0}$$
$$\nabla \cdot \mathbf{B} = 0$$
$$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}$$
$$\nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}$$

### Quantum Mechanics

**Schrödinger Equation:**
$$i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \hat{H} \Psi(\mathbf{r},t)$$

**Heisenberg Uncertainty Principle:**
$$\Delta x \Delta p \geq \frac{\hbar}{2}$$

</details>

## Important Notes

<details>
<summary>⚠️ LaTeX in Markdown Tips</summary>

### Syntax Guidelines

1. **Use double dollar signs** for display math: `$$formula$$`
2. **Use single dollar signs** for inline math: `$formula$` (may not work in all renderers)
3. **Escape special characters** when needed
4. **Leave blank lines** before and after display math for better rendering

### Common Issues

- Some Markdown renderers require blank lines around LaTeX blocks
- GitHub supports LaTeX in markdown files but may have limitations
- Always test your formulas in the target environment

### Best Practices

- Keep formulas readable with proper spacing
- Use `\text{}` for text within formulas: $$P(\text{success}) = 0.95$$
- Use `\,` for thin spaces and `\quad` for larger spaces
- Break long formulas across multiple lines when possible

</details>
```
```

Key points for using LaTeX in collapsible sections:

1. **Double dollar signs** (`$$`) work best for display math
2. **Leave blank lines** before and after LaTeX blocks for proper rendering
3. **Test compatibility** - different platforms may render differently
4. **Use proper escaping** for special characters
5. **Keep formulas organized** with clear headings and explanations

The collapsible sections work great for organizing mathematical content by topic, making it easy for readers to find specific formulas or proofs without overwhelming them with too much content at once.
