## 1. Complex Numbers (Higher Level Only)

### Definition and Forms

- **Standard Form**: z = a + bi where a, b ∈ ℝ and i² = -1
- **Real Part**: Re(z) = a
- **Imaginary Part**: Im(z) = b
- **Complex Conjugate**: z̄ = a - bi

### Operations with Complex Numbers

- **Addition**: (a + bi) + (c + di) = (a + c) + (b + d)i
- **Subtraction**: (a + bi) - (c + di) = (a - c) + (b - d)i
- **Multiplication**: (a + bi)(c + di) = (ac - bd) + (ad + bc)i
- **Division**: (a + bi)/(c + di) = [(a + bi)(c - di)]/[c² + d²]

### Modulus and Argument

- **Modulus**: |z| = √(a² + b²)
- **Argument**: arg(z) = tan⁻¹(b/a) (considering quadrant)

### Polar Form

- z = r(cos θ + i sin θ) = re^(iθ)
- **De Moivre's Theorem**: (cos θ + i sin θ)ⁿ = cos(nθ) + i sin(nθ)

## 2. Sequences and Series

### Arithmetic Sequences

- **General Term**: aₙ = a₁ + (n-1)d
- **Common Difference**: d = aₙ₊₁ - aₙ
- **Sum of n terms**: Sₙ = n/2[2a₁ + (n-1)d] or Sₙ = n/2(a₁ + aₙ)

### Geometric Sequences

- **General Term**: aₙ = a₁ × r^(n-1)
- **Common Ratio**: r = aₙ₊₁/aₙ
- **Sum of n terms**: Sₙ = a₁(1-rⁿ)/(1-r) when r ≠ 1
- **Sum to Infinity**: S∞ = a₁/(1-r) when |r| < 1

### Sigma Notation

- ∑ₖ₌₁ⁿ k = n(n+1)/2
- ∑ₖ₌₁ⁿ k² = n(n+1)(2n+1)/6
- ∑ₖ₌₁ⁿ k³ = [n(n+1)/2]²

## 3. Functions and Their Properties

### Function Notation and Domain/Range

- **Function**: f: A → B where each element in A maps to exactly one element in B
- **Domain**: Set of all possible input values
- **Range**: Set of all possible output values
- **Composite Functions**: (f ∘ g)(x) = f(g(x))

### Types of Functions

- **One-to-one (Injective)**: Each output corresponds to exactly one input
- **Onto (Surjective)**: Every element in codomain has a pre-image
- **Bijective**: Both one-to-one and onto

### Inverse Functions

- **Definition**: f⁻¹(x) exists if f is one-to-one
- **Property**: f(f⁻¹(x)) = x and f⁻¹(f(x)) = x
- **Finding Inverse**: Replace f(x) with y, swap x and y, solve for y

## 4. Polynomial Functions

### General Form

P(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀

### The Remainder Theorem

If polynomial P(x) is divided by (x - a), the remainder is P(a).

### The Factor Theorem

(x - a) is a factor of P(x) if and only if P(a) = 0.

### Polynomial Division

- **Long Division**: Systematic method for dividing polynomials
- **Synthetic Division**: Shortcut method when dividing by (x - a)

### Finding Roots

- **Rational Root Theorem**: Possible rational roots are ±p/q where p divides constant term and q divides leading coefficient
- **Fundamental Theorem of Algebra**: A polynomial of degree n has exactly n roots (counting multiplicity)

## 5. Exponential and Logarithmic Functions

### Exponential Functions

- **General Form**: f(x) = aˣ where a > 0, a ≠ 1
- **Natural Exponential**: f(x) = eˣ where e ≈ 2.718
- **Properties**:
    - aˣ × aʸ = aˣ⁺ʸ
    - aˣ ÷ aʸ = aˣ⁻ʸ
    - (aˣ)ʸ = aˣʸ
    - a⁰ = 1

### Logarithmic Functions

- **Definition**: log_a(x) = y if and only if aʸ = x
- **Common Logarithm**: log₁₀(x) = log(x)
- **Natural Logarithm**: logₑ(x) = ln(x)

### Properties of Logarithms

- log_a(xy) = log_a(x) + log_a(y)
- log_a(x/y) = log_a(x) - log_a(y)
- log_a(xⁿ) = n log_a(x)
- log_a(a) = 1
- log_a(1) = 0
- a^(log_a(x)) = x

### Change of Base Formula

log_a(x) = log_b(x)/log_b(a) = ln(x)/ln(a)

### Solving Exponential and Logarithmic Equations

- **Exponential**: Take logarithm of both sides
- **Logarithmic**: Convert to exponential form or use properties

## 6. Rational Functions

### Definition

f(x) = P(x)/Q(x) where P(x) and Q(x) are polynomials and Q(x) ≠ 0

### Domain and Vertical Asymptotes

- **Domain**: All real numbers except where Q(x) = 0
- **Vertical Asymptotes**: x = a where Q(a) = 0 but P(a) ≠ 0

### Horizontal Asymptotes

- If degree of P < degree of Q: y = 0
- If degree of P = degree of Q: y = ratio of leading coefficients
- If degree of P > degree of Q: no horizontal asymptote

### Oblique/Slant Asymptotes

Occur when degree of P is exactly one more than degree of Q. Found by polynomial long division.

## 7. Transformations of Functions

### Vertical Transformations

- f(x) + k: shift up k units
- f(x) - k: shift down k units
- af(x): vertical stretch by factor a (if |a| > 1) or compression (if 0 < |a| < 1)
- -f(x): reflection over x-axis

### Horizontal Transformations

- f(x + h): shift left h units
- f(x - h): shift right h units
- f(ax): horizontal compression by factor 1/a (if |a| > 1) or stretch (if 0 < |a| < 1)
- f(-x): reflection over y-axis

### Combined Transformations

f(x) = a·g(b(x - h)) + k where g is the parent function

## 8. Solving Systems of Equations (Higher Level)

### Linear Systems

- **Two variables**: Use substitution, elimination, or matrix methods
- **Three variables**: Use elimination or matrix methods

### Non-linear Systems

- Systems involving quadratic, exponential, or other non-linear equations
- Use substitution, graphing, or algebraic manipulation

### Matrix Methods (Higher Level Only)

- **Gaussian Elimination**: Row operations to solve systems
- **Cramer's Rule**: Using determinants to solve systems
- **Matrix Inverses**: A⁻¹ exists if det(A) ≠ 0

## 9. Partial Fractions (Higher Level Only)

### Purpose

Decompose rational functions into simpler fractions for integration or other operations.

### Types of Decomposition

- **Linear Factors**: A/(x-a) + B/(x-b)
- **Repeated Linear Factors**: A/(x-a) + B/(x-a)²
- **Quadratic Factors**: (Ax+B)/(x²+px+q)

### Method

1. Factor denominator completely
2. Set up partial fraction form
3. Clear denominators
4. Solve for unknown coefficients

## 10. Mathematical Induction (Higher Level Only)

### Principle

To prove a statement P(n) is true for all natural numbers n ≥ n₀:

1. **Base Case**: Show P(n₀) is true
2. **Inductive Step**: Assume P(k) is true, then prove P(k+1) is true

### Applications

- Proving formulas for sums
- Proving divisibility statements
- Proving inequalities

## 11. Binomial Theorem

### Binomial Expansion

(a + b)ⁿ = ∑ₖ₌₀ⁿ (n choose k) aⁿ⁻ᵏbᵏ

### Binomial Coefficients

(n choose k) = n!/(k!(n-k)!) = ₙCₖ

### Pascal's Triangle

Each entry is the sum of the two entries above it.

### General Term

The (r+1)th term in the expansion of (a + b)ⁿ is: Tᵣ₊₁ = (n choose r) aⁿ⁻ʳbʳ

## 12. Applications and Problem Solving

### Financial Mathematics

- **Compound Interest**: A = P(1 + r/n)ⁿᵗ
- **Continuous Compounding**: A = Pe^(rt)
- **Annuities**: Present and future value calculations

### Growth and Decay Models

- **Exponential Growth**: N(t) = N₀e^(kt) where k > 0
- **Exponential Decay**: N(t) = N₀e^(-kt) where k > 0
- **Half-life and Doubling Time**

### Optimization Problems

Using calculus concepts to find maximum and minimum values in real-world contexts.

## Key Problem-Solving Strategies

1. **Identify the type** of function or equation
2. **Choose appropriate methods** based on the problem type
3. **Check domains and restrictions** especially for rational and logarithmic functions
4. **Verify solutions** in original equations
5. **Use technology appropriately** for verification and exploration
6. **Interpret results** in context of real-world problems

## Common Examination Topics

- Sequences and series applications
- Exponential and logarithmic equation solving
- Function transformations and graphing
- Complex number operations (Higher Level)
- Polynomial factoring and root finding
- Rational function analysis
- System solving with various methods
- Mathematical proof techniques (Higher Level)

## Important Formulas to Remember

### Sequences and Series

- Arithmetic: aₙ = a + (n-1)d, Sₙ = n/2[2a + (n-1)d]
- Geometric: aₙ = ar^(n-1), Sₙ = a(1-rⁿ)/(1-r), S∞ = a/(1-r)

### Logarithms

- Change of base: log_a(x) = ln(x)/ln(a)
- Properties: log(xy) = log(x) + log(y), log(x/y) = log(x) - log(y)

### Complex Numbers (Higher Level)

- |z| = √(a² + b²)
- De Moivre's Theorem: (cos θ + i sin θ)ⁿ = cos(nθ) + i sin(nθ)

### Financial

- Compound Interest: A = P(1 + r)ⁿ
- Continuous: A = Pe^(rt)