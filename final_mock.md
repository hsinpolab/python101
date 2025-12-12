# [Incomplete Words](https://projecteuler.net/problem=657)  
In the context of **formal languages**, any finite sequence of letters of a given **alphabet** $\Sigma$ is called a **word** over $\Sigma$. 
We call a word *incomplete* if it does not contain every letter of $\Sigma$.

For example, using the alphabet $\Sigma = \{a, b, c\}$, `ab`, `abab`, and `` (the empty word) are incomplete words over $\Sigma$, while `abac` is a complete word over $\Sigma$.

Given an alphabet $\Sigma$ of $\alpha$ letters, we define $I(\alpha, n)$ to be the number of incomplete words over $\Sigma$ with a length not exceeding $n$.

For example, $I(3, 0) = 1$, $I(3, 2) = 13$, and $I(3, 4) = 79$.

Find $I(10^7, 10^{12})$. Give your answer modulo $1\,000\,000\,007$.

# [2025](https://projecteuler.net/problem=932)
For the year $2025$
$$2025 = (20 + 25)^2$$
Given positive integers $a$ and $b$, the concatenation $ab$ we call a $2025$-number if $ab = (a+b)^2$.
Other examples are $3025$ and $81$.
Note $9801$ is not a $2025$-number because the concatenation of $98$ and $1$ is $981$.


Let $T(n)$ be the sum of all $2025$-numbers with $n$ digits or less. You are given $T(4) = 5131$.


Find $T(16)$.

# [Two-Dimensional Recurrence](https://projecteuler.net/problem=940)

The Fibonacci sequence $(f_i)$ is the unique sequence such that

- $f_0=0$
- $f_1=1$
- $f_{i+1}=f_i+f_{i-1}$

Similarly, there is a unique function $A(m,n)$ such that

- $A(0,0)=0$  
- $A(0,1)=1$  
- $A(m+1,n)=A(m,n+1)+A(m,n)$  
- $A(m+1,n+1)=2A(m+1,n)+A(m,n)$

Define $S(k)=\sum_{i=2}^k\sum_{j=2}^k A(f_i,f_j)$.  
For example  


$S(3)=A(1,1)+A(1,2)+A(2,1)+A(2,2)$  
$=2+5+7+16$  
$=30$  
You are also given $S(5)=10396$.

Find $S(50)$, giving your answer modulo $1123581313$.

# [Powers or $1+\sqrt 7$](https://projecteuler.net/problem=752)

When $(1+\sqrt 7)$ is raised to an integral power, $n$, we always get a number of the form $(a+b\sqrt 7)$.
We write $(1+\sqrt 7)^n = \alpha(n) + \beta(n)\sqrt 7$.


For a given number $x$ we  define $g(x)$ to be the smallest positive integer $n$ such that:  
$\alpha(n) \equiv 1 \pmod x\qquad \text{and }$  
$\beta(n) \equiv 0 \pmod x$

and $g(x) = 0$ if there is no such value of $n$. For example, $g(3) = 0$, $g(5) = 12$.

Further define
$G(N) = \sum_{x=2}^N g(x) $  
You are given $G(10^2) = 28891$ and $G(10^3)  = 13131583$.

Find $G(10^6)$.

