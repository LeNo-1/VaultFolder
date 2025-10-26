
#DifferentialCalculus #mathsMain 
#### Limits
if $f(x)=\frac{x^2-25}{x-5}, x\in \mathbb{R}$  what value does f(x) tend towards as x gets closer to 5

| x   | f(x) + | x   | f(x) - |
| --- | ------ | --- | ------ |
| 4.7 | 9.7    | 5.3 | 10.3   |
| 4.8 | 9.8    | 5.2 | 10.2   |
| 4.9 | 9.9    | 5.1 | 10.1   |
- as x gets closer to 5 from either side, f(x) tends towrds 10 or $\lim_{x\to 5} f(x)=10$ 
- $$\lim_{x \to 5} \frac{x^2-25}{x-5} \to \lim_{x \to 5} \frac{(x-5)(x+5)}{x-5} \to \lim_{x \to 5} (x+5)=10$$
> A limit is a point that a graph approaches
- It may or may not touch that point

If the graph is *continuous* the line approaches the point from both direction
### Explanation: Why the function $f(x) = \frac{1}{x-2}$, $4 \leq x \leq 7$, $x \neq 2$, $x \in \mathbb{R}$, is not continuous.

#### Algebraic Method:
$f(2) = \frac{1}{2-2} = \frac{1}{0}$ which is not defined.

#### Graphical Approach:
![[diagram-20250903-1.svg]]

### Differentiation from First Principles
![[diagram-20250903(2).svg]]

slope of chord ab =$\frac{y_2-y_2}{x_2-x_1}$ 
$$=\frac{f(x+h)-f(x)}{x+h-x} \to \frac{f(x+h)-f(x)}{h}$$
- This is equal to $\frac{dy}{dx} or f\prime(x)$ 
### Differentiating Polynomial Functions and Functions with Rational Powers
The Derivative of $x^n$ :
- if $y=x^n$ then $\frac{dy}{dx}=nx^{n-1}$ 
- if $y=a$ where a is any constant, then $\frac{dy}{dx}=0$
- if $y=ax^n$ where a is any constant, then $\frac{dy}{dx}=anx^{n-1}$
#### The Chain Rule
u and v are both functions and f is the composite functions defined by:
$f\prime(x)=u((v(x))$ In this case $f\prime (x)=\frac{du}{dv}\times \frac{dy}{dx}$   

#### Product Rule
$$f(x)=u(x)v(x)\to f\prime(x)=u(x)v\prime v(x)+v(x)u\prime (x)$$
- $$\frac{dy}{dx}=u\frac{dv}{dx}+v\frac{du}{dx}$$

#### Quotient Rule
$$f(x)=\frac{u(x)}{v(x)}\to f\prime(x)=\frac{v(x)u\prime(x)-u(x)v\prime(x)}{[v(x)]^2}$$
- $$\frac{dy}{dx}= \frac{v\frac{du}{dx}-u\frac{dv}{dx}}{v(x)^2}$$
#### Trigonometric Functions

| f(x)   | f'(x)      |
| ------ | ---------- |
| Sin(x) | $Cos(x)$   |
| Cos(x) | $-Sin(x)$  |
| Tan(x) | $Sec^2(x)$ |

