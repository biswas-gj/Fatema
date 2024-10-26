Let's solve this problem step-by-step.

Given:
\[
F(x, y) = (3y - 1, 1 - x)
\]

### Part (a): Evaluate \( F(0, 0) \) and \( F(1, 4) \).

1. **\( F(0, 0) \):**
   \[
   F(0, 0) = (3 \cdot 0 - 1, 1 - 0) = (-1, 1)
   \]

2. **\( F(1, 4) \):**
   \[
   F(1, 4) = (3 \cdot 4 - 1, 1 - 1) = (12 - 1, 0) = (11, 0)
   \]

So, the answers are:
- \( F(0, 0) = (-1, 1) \)
- \( F(1, 4) = (11, 0) \)

---

### Part (b): Is \( F \) one-to-one?

To determine if \( F \) is one-to-one, we need to check if \( F(x_1, y_1) = F(x_2, y_2) \) implies \( (x_1, y_1) = (x_2, y_2) \).

Suppose:
\[
F(x_1, y_1) = F(x_2, y_2)
\]
Then:
\[
(3y_1 - 1, 1 - x_1) = (3y_2 - 1, 1 - x_2)
\]

This gives the equations:
1. \( 3y_1 - 1 = 3y_2 - 1 \)
2. \( 1 - x_1 = 1 - x_2 \)

From the first equation:
\[
3y_1 = 3y_2 \Rightarrow y_1 = y_2
\]

From the second equation:
\[
x_1 = x_2
\]

Since \( F(x_1, y_1) = F(x_2, y_2) \) implies \( (x_1, y_1) = (x_2, y_2) \), \( F \) is one-to-one.

---

### Part (c): Is \( F \) onto?

To check if \( F \) is onto, we need to see if for any point \( (a, b) \) in \( \mathbb{R} \times \mathbb{R} \), there exists \( (x, y) \) such that:
\[
F(x, y) = (a, b)
\]

That is, we need:
\[
(3y - 1, 1 - x) = (a, b)
\]

This gives:
1. \( 3y - 1 = a \)
2. \( 1 - x = b \)

From the first equation:
\[
y = \frac{a + 1}{3}
\]

From the second equation:
\[
x = 1 - b
\]

Since we can solve for \( x \) and \( y \) for any \( (a, b) \), \( F \) is onto.

---

### Part (d): Is \( F \) a one-to-one correspondence?

Since \( F \) is both one-to-one and onto, it is a one-to-one correspondence (bijective). 

To find \( F^{-1} \), we need to express \( (x, y) \) in terms of \( (a, b) \), where \( (a, b) = F(x, y) = (3y - 1, 1 - x) \).

From part (c), we derived:
\[
y = \frac{a + 1}{3}
\]
\[
x = 1 - b
\]

Thus, the inverse function is:
\[
F^{-1}(a, b) = \left(1 - b, \frac{a + 1}{3}\right)
\]
