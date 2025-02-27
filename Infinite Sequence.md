# Infinite Sequence

## Problem

**If \( x^x^x^x^x ... = 2 \), where \( a^b = a^b \), what is \( x \)?**

<details>
<summary>Click to see the solution</summary>

### Solution

At first glance, this problem may seem challenging, but a straightforward analysis leads to an elegant solution.

From the original equation:
\[
x^x^x^x^x ... = 2
\]

We observe that the infinite sequence implies:
\[
\lim_{n \to \infty} x^x^x^x^x ... = 2 (n items) \Leftrightarrow \lim_{n \to \infty} x^x^x^x^x^x ... = 2 (n +1 items)
\]

This means that the sequence converges to 2, regardless adding or minus one \(x\) terms in the exponentiation. Hence, the following equality holds:
\[
x^x^x^x^x ... = x^(x^x^x^x^x ...) = x^2 = 2
\]

Thus, the equation simplifies to:
\[
x^2 = 2
\]

Taking the square root of both sides, we find:
\[
x = \sqrt{2}
\]

### Final Answer:
\[
x = \sqrt{2}
\]

</details>
