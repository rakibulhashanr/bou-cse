## Domain and Range of a Function

### ✅ Simple Definition (Not Bookish)

A **function** takes an input, does something to it, and gives you an output.

* The **domain** is all the possible values you are *allowed* to give as input.
* The **range** is all the values you *get back* as output.

> You can think of a **function** like a **vending machine**.

* The **buttons you can press** (like A1, B2, C3) — that’s the **domain**.
* The **snacks that come out** — that’s the **range**.

---

### 🎯 Formal But Simple Definition:

* **Domain** of a function is the complete set of all possible input values (**x**) for which the function is defined.
* **Range** of a function is the complete set of all possible output values (**f(x)**) that the function can give.

---

### 🧠 Example:

Let’s say we have a function:
  **f(x) = x²**

#### Step 1: Domain

You can put **any real number** into x (positive, negative, or zero), and you will get a valid result.

✅ So, the domain is: **All real numbers**
  In symbols: **x ∈ ℝ**

#### Step 2: Range

No matter what number you put, the output will always be **zero or positive** (because square of any real number is ≥ 0).

✅ So, the range is: **All real numbers greater than or equal to 0**
  In symbols: **f(x) ≥ 0** or **f(x) ∈ \[0, ∞)**

---
### **Example 2:**

Given the function:

$$
f(x) = 3x^2 + x + 2
$$

Find the **domain** and **range** of the function.

---

### ✅ **Domain of f(x):**

The function $f(x) = 3x^2 + x + 2$ is a **polynomial function**.
Polynomial functions are defined for **all real numbers**.

So,

$$
\text{Domain } D_f = \{x \in \mathbb{R}\} = \mathbb{R}
$$

---

### ✅ **Range of f(x):**

Let,

$$
y = f(x) = 3x^2 + x + 2 \tag{1}
$$

Now, rearrange (1) to form a quadratic in $x$:

$$
3x^2 + x + (2 - y) = 0
$$

This is a quadratic equation in $x$.
For real values of $x$, the **discriminant** must be ≥ 0.

---

**Discriminant formula**:

$$
D = b^2 - 4ac
$$

In our case:

* $a = 3$,
* $b = 1$,
* $c = 2 - y$

So,

$$
D = 1^2 - 4 \cdot 3 \cdot (2 - y) = 1 - 12(2 - y)
= 1 - 24 + 12y = 12y - 23
$$

To get real $x$, we need:

$$
12y - 23 \geq 0 \Rightarrow y \geq \frac{23}{12}
$$

---

### ✅ **Range:**

So, the range of the function is:

$$
R_f = \left[ \frac{23}{12}, \infty \right)
$$

---

### 📌 Final Answer:

* **Domain**: $\mathbb{R}$
* **Range**: $\left[ \frac{23}{12}, \infty \right)$

---
$$
f(x) = \sqrt{x - 1} + \sqrt{5 - x}, \quad \text{for } x \in [1, 5]
$$

---

### ✅ Step 1: Understand the Function's Behavior

This function is the **sum of two square roots**, and their **domains are opposite** in nature:

* $\sqrt{x - 1}$ **increases** as $x$ increases.
* $\sqrt{5 - x}$ **decreases** as $x$ increases.

So when $x = 1$, the first term is minimum and the second term is maximum.
When $x = 5$, the first term is maximum and the second term is minimum.

---

### ✅ Step 2: Find Minimum and Maximum Values

#### 👉 At $x = 1$:

$$
f(1) = \sqrt{1 - 1} + \sqrt{5 - 1} = \sqrt{0} + \sqrt{4} = 0 + 2 = 2
$$

#### 👉 At $x = 5$:

$$
f(5) = \sqrt{5 - 1} + \sqrt{5 - 5} = \sqrt{4} + \sqrt{0} = 2 + 0 = 2
$$

#### 👉 At $x = 3$ (Midpoint for symmetry):

$$
f(3) = \sqrt{3 - 1} + \sqrt{5 - 3} = \sqrt{2} + \sqrt{2} = 2\sqrt{2} \approx 2.828
$$

This is the **maximum value**.

---

### ✅ Step 3: Final Answer

* **Minimum value**: 2
* **Maximum value**: $2\sqrt{2} \approx 2.828$

---

### 📌 Final Range:

$$
\boxed{\text{Range } = [2, 2\sqrt{2}]}
$$
