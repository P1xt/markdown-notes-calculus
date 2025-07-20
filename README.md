# **Chapter 1**

Summary, created after skimming TOC and Guide Questions, reading the chapter, filling out my definitions list, and taking notes on the main concepts of this module:
In order to solve problems involving limits and continuity, I should understand what a limit is, what continuity is, and understand the 9 theorems presented in this module. Were I to make flash cards, I'd do so for all terms in the definitions list, and for each of the theorems.

<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [**Chapter 1**](#chapter-1)
  - [**First look**](#first-look)
    - [**Contents page (page iii)**](#contents-page-page-iii)
    - [**Questions to guide your review (page 103)**](#questions-to-guide-your-review-page-103)
    - [**Summary of big ideas**](#summary-of-big-ideas)
  - [**Definitions I want to fill out by the end of the chapter**](#definitions-i-want-to-fill-out-by-the-end-of-the-chapter)
  - [**Explanation of formal definition of a limit**](#explanation-of-formal-definition-of-a-limit)
    - [**Plain English Explanation:**](#plain-english-explanation)
    - [**Formal (Symbolic) Definition:**](#formal-symbolic-definition)
    - [**What It Really Means:**](#what-it-really-means)
    - [**Example:**](#example)
  - [**Important theorems**](#important-theorems)
    - [**Theorem 1**](#theorem-1)
      - [**Rules**](#rules)
    - [**Theorem 2**](#theorem-2)
    - [**Theorem 3**](#theorem-3)
      - [**How to Eliminate Zero Denominators Algebraically**](#how-to-eliminate-zero-denominators-algebraically)
    - [**Theorem 4**](#theorem-4)
      - [**Extensions of the Limit Concept**](#extensions-of-the-limit-concept)
        - [**One-Sided Limits**](#one-sided-limits)
        - [**Infinite Limits**](#infinite-limits)
    - [**Theorem 5: Relationship Between One-Sided and Two-Sided Limits**](#theorem-5-relationship-between-one-sided-and-two-sided-limits)
  - [**Continuity**](#continuity)
    - [**Basic Terms**](#basic-terms)
    - [**Continuity at a Point**](#continuity-at-a-point)
      - [**Removable Discontinuity**](#removable-discontinuity)
      - [**Jump Discontinuity**](#jump-discontinuity)
      - [**Infinite Discontinuity**](#infinite-discontinuity)
      - [**Continuous at a Left or Right Endpoint**](#continuous-at-a-left-or-right-endpoint)
      - [**Continuity on Intervals**](#continuity-on-intervals)
  - [**Key Theorems About Continuity**](#key-theorems-about-continuity)
    - [**Theorem 6: Continuity of Algebraic Combinations**](#theorem-6-continuity-of-algebraic-combinations)
    - [**Theorem 7: Continuity of Polynomials and Rational Functions**](#theorem-7-continuity-of-polynomials-and-rational-functions)
    - [**Theorem 8: Continuity of Composite Functions**](#theorem-8-continuity-of-composite-functions)
    - [**Theorem 9: The Intermediate Value Theorem (IVT)**](#theorem-9-the-intermediate-value-theorem-ivt)

<!-- TOC end --

---

<!-- TOC --<a name="first-look"</a
## **First look**

<!-- TOC --><a name="contents-page-page-iii"></a>
### **Contents page (page iii)**
Chapter 1 is about Limits and Continuity introduces:
- rates of change
- limits
- rules for finding limits
- target values
- the formal definition of a limit
- extensions to the limit concept
- continuity
- tangent lines

---

<!-- TOC --><a name="questions-to-guide-your-review-page-103"></a>
### **Questions to guide your review (page 103)**
Reading through the questions, I see that the following concepts will be important:
- knowing how to find the average rate of change
- knowing how to decide what limit to calculate
- being able to figure out whether what happens at a particular point affect the existence of and value of a limit
- knowing what theorems are there to help easily find limits
- knowing what one sided limits are
- knowing how to control the input of a function to scope the limit
- explaining limit notation in words
- knowing what a continuous function is and what conditions have to be present for a function to be continuous
- being able to look at a graph and tell where it is continuous
- what does left continous and right continuous mean and how do you figure them out
- being able to figure continuity out for a variety of functions like:
    - polynomials
    - trig functions
    - rational powers
    - combinations of functions
    - composites of functions
    - absolute value of functions
- be able to explain continuity on an interval
- be able explain what it means for a function to be continuous
- know what properties does a function need to have to be continuous on an interval
- what does it mean for a line to be tangent to a curve at a specific point

---

<!-- TOC --><a name="summary-of-big-ideas"></a>
### **Summary of big ideas**
The main theme for this chapter is limits and continuity. By the end of it I should understand what limits are, know the main theorms for solving them, understand what continuity of a function is and why it's important to understand continuity and how it relates to limits, and understand how to figure out limits for a variety of functions.

---

<!-- TOC --><a name="definitions-i-want-to-fill-out-by-the-end-of-the-chapter"></a>
## **Definitions I want to fill out by the end of the chapter**

I'll fill these out as I go through the chapter

| Term                                 | Definition                                                                                                                                                                                                                                  |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **rates of change**                  | The average rate of change for a function is how much the output (y) changes compared to the input (x); essentially the slope between two points.                                                                                           |
| **limit**                            | A limit tells us what value a function is getting close to as the input (x) gets close to a certain number.                                                                                                                                 |
| **limit notation**                   | $\lim_{x \to x_0} f(x) = L$ means “as $x$ gets close to $x_0$, the function $f(x)$ gets close to the value $L$.”                                                                                                                            |
| **rules for finding limits**         | These are shortcuts and properties—like the sum, difference, product, quotient, and power rules—that help us calculate limits more easily without needing to graph.                                                                         |
| **one-sided limits**                 | A one-sided limit looks at what value a function approaches from only one side—either from the left ($x \to x_0^-$) or from the right ($x \to x_0^+$).                                                                                      |
| **target values**                    | The value that a function approaches (the “target”) as the input gets close to a specific number, regardless of what the function actually equals there.                                                                                    |
| **the formal definition of a limit** | Uses ε (epsilon) and δ (delta) to precisely define what it means for a function to get close to a value: for every small distance (ε) you want between $f(x)$ and the limit, there is a small range (δ) around $x_0$ where this holds true. |
| **extensions to the limit concept**  | Includes ideas like infinite limits (function grows without bound), limits at infinity (what happens as $x$ becomes very large or small), and limits involving piecewise functions or discontinuities.                                      |
| **continuity**                       | A function is continuous at a point if the limit exists at that point, the function is defined there, and the limit equals the actual function value—meaning there are no jumps, holes, or breaks.                                          |
| **intervals**                        | A continuous stretch of numbers on the x-axis where the function behaves a certain way; limits can be analyzed over open, closed, or infinite intervals.                                                                                    |
| **tangent lines**                    | A tangent line touches a curve at one point and shows the direction the curve is heading at that exact point; its slope is found using a limit of the average rate of change.                                                               |

---
<!-- TOC --><a name="explanation-of-formal-definition-of-a-limit"></a>
## **Explanation of formal definition of a limit**

<!-- TOC --><a name="plain-english-explanation"></a>
### **Plain English Explanation:**

The **formal definition of a limit** is a precise way to say:

> “As $x$ gets really, really close to a number, $f(x)$ gets really, really close to a specific value.”

But how close is “really close”? And how can we **prove** it?

That’s where **epsilon (ε)** and **delta (δ)** come in:

* **ε (epsilon)** is how close you want $f(x)$ to get to the limit value (think vertical closeness).
* **δ (delta)** is how close you need to make $x$ to the target number (horizontal closeness) to get that result.

The formal definition says:

> If you want to make the function’s output $f(x)$ as close as you like to the limit $L$, then you can always find a small distance $\delta$ such that if $x$ is within $\delta$ units of the target number $x_0$, then $f(x)$ will be within $\varepsilon$ units of $L$.

Think of it as a **promise**:
If someone picks an ε, saying "I want $f(x)$ to be within this range of the limit,"
you can find a δ such that, "Sure—then just make sure $x$ is this close to $x_0$, and we’re good."

---

<!-- TOC --><a name="formal-symbolic-definition"></a>
### **Formal (Symbolic) Definition:**

We say

$$
\lim_{x \to x_0} f(x) = L
$$

**if and only if**:

For every $\varepsilon > 0$, there exists a $\delta > 0$ such that
whenever $0 < |x - x_0| < \delta$, it follows that $|f(x) - L| < \varepsilon$.

---

<!-- TOC --><a name="what-it-really-means"></a>
### **What It Really Means:**

* $x$ is **not equal** to $x_0$, but very close.
* $f(x)$ is **not required** to be equal to $L$ at $x_0$—just very close to $L$ when $x$ is close to $x_0$.
* This definition works even when the function **isn't defined** at $x_0$, or if there’s a **hole** in the graph.

---

<!-- TOC --><a name="example"></a>
### **Example:**

Let’s say

$$
\lim_{x \to 2} (3x + 1) = 7
$$

If someone says:

“I want $f(x)$ to stay within 0.01 of 7 (so $\varepsilon = 0.01$),”

You can reply:

“Then keep $x$ within 0.0033 of 2 (so $\delta = 0.0033$), and it’ll work.”

This back-and-forth guarantees that no matter how tight the output range is, we can always make the input close enough to hit it.

<!-- TOC --><a name="important-theorems"></a>
## **Important theorems**

<!-- TOC --><a name="theorem-1"></a>
### **Theorem 1**
<!-- TOC --><a name="rules"></a>
### **Rules**


| Rule                       | Explanation                                                                                                                                               |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sum Rule**               | The limit of a sum is the sum of the limits. In other words, you can take the limit of each part separately and then add them together.                   |
| **Difference Rule**        | The limit of a difference is the difference of the limits. Just take the limit of each part and subtract.                                                 |
| **Product Rule**           | The limit of a product is the product of the limits. Take the limit of each factor and then multiply the results.                                         |
| **Constant Multiple Rule** | If you're multiplying a function by a constant, you can pull the constant out of the limit. Then just multiply the constant by the limit of the function. |
| **Quotient Rule**          | The limit of a quotient is the quotient of the limits—as long as the limit of the denominator isn’t zero.                                                 |
| **Power Rule**             | If a function is raised to a power, you can take the limit first, then raise the result to that power.                                                    |


<!-- TOC --><a name="theorem-2"></a>
### **Theorem 2**

**Limits of polynomials can be found by substitution**

**Plain English Explanation:**
If you’re working with a polynomial (like $x^2 + 5x - 3$), and you want to find its limit as $x$ approaches a certain number, you can just **plug that number in**. Polynomials are continuous everywhere, so they don’t have holes, jumps, or asymptotes.

**Example:**

$$
\lim_{x \to 2}(x^2 + 3x - 1) = 2^2 + 3(2) - 1 = 4 + 6 - 1 = 9
$$

---

<!-- TOC --><a name="theorem-3"></a>
### **Theorem 3**

**Limits of rational functions can be found by substitution if the limit of the denominator is not zero**

**Plain English Explanation:**
Rational functions are fractions made of polynomials. If plugging in a number for $x$ **doesn't make the denominator zero**, then you can just plug the number in to find the limit.

**Example (safe):**

$$
\lim_{x \to 1} \frac{x^2 + 1}{x + 2} = \frac{1^2 + 1}{1 + 2} = \frac{2}{3}
$$

But if the **denominator becomes zero**, substitution doesn’t work — you’ll need to try simplifying first (see below).


---

<!-- TOC --><a name="how-to-eliminate-zero-denominators-algebraically"></a>
### **How to Eliminate Zero Denominators Algebraically**

Sometimes when you substitute, you get **0 in the denominator**, which is undefined. If this happens but the limit still exists, you can try:

* **Canceling a common factor:**
  Factor both top and bottom and cancel terms that are the same.

  **Example:**

  $$
  \lim_{x \to 3} \frac{x^2 - 9}{x - 3} = \lim_{x \to 3} \frac{(x - 3)(x + 3)}{x - 3} = \lim_{x \to 3} (x + 3) = 6
  $$

* **Creating and canceling a common factor:**
  Multiply top and bottom by a conjugate or do algebra to reveal a common factor that cancels.

  **Example (with conjugate):**

  $$
  \lim_{x \to 0} \frac{\sqrt{x + 1} - 1}{x} \\
  \text{Multiply by the conjugate: } \frac{\sqrt{x + 1} - 1}{x} \cdot \frac{\sqrt{x + 1} + 1}{\sqrt{x + 1} + 1} = \frac{x}{x(\sqrt{x + 1} + 1)} = \frac{1}{\sqrt{x + 1} + 1}
  $$

  Now you can plug in $x = 0$:
  $\frac{1}{2}$

---

<!-- TOC --><a name="theorem-4"></a>
### **Theorem 4**

**The Sandwich Theorem (Squeeze Theorem)**

**Plain English Explanation:**
If a function is "trapped" between two other functions that both approach the same limit, then the trapped function has to go to that same limit too.



---

<!-- TOC --><a name="extensions-of-the-limit-concept"></a>
### **Extensions of the Limit Concept**

---

<!-- TOC --><a name="one-sided-limits"></a>
#### **One-Sided Limits**

**Plain English Explanation:**
A **one-sided limit** looks at how a function behaves as the input gets close to a number **from just one side**:

* **Left-hand limit**: what $f(x)$ approaches as $x$ comes **from the left** (written as $\lim_{x \to a^-} f(x)$)
* **Right-hand limit**: what $f(x)$ approaches as $x$ comes **from the right** (written as $\lim_{x \to a^+} f(x)$)

**Why it matters:**
Sometimes a function behaves **differently on each side** of a number. One-sided limits help us describe and analyze that.

**Example:**
For the function

$$
f(x) = 
\begin{cases}
1, & x < 0 \\
2, & x > 0
\end{cases}
$$

* $\lim_{x \to 0^-} f(x) = 1$
* $\lim_{x \to 0^+} f(x) = 2$
* Since the left and right limits **don’t match**, the full (two-sided) limit at $x = 0$ **does not exist**.

---

<!-- TOC --><a name="infinite-limits"></a>
#### **Infinite Limits**

**Plain English Explanation:**
An **infinite limit** means that as $x$ gets close to some value, the function's output **grows without bound**—either positively or negatively.

* If $f(x)$ becomes very large, we write:
  $\lim_{x \to a} f(x) = \infty$
* If $f(x)$ becomes very negative:
  $\lim_{x \to a} f(x) = -\infty$

**Important note:**
Infinite limits **do not exist in the usual sense**, but we use the infinity symbol to describe their behavior.

**Example:**

$$
\lim_{x \to 0^+} \frac{1}{x} = \infty  
\quad \text{and} \quad  
\lim_{x \to 0^-} \frac{1}{x} = -\infty
$$

The function blows up as it nears 0 from either side.

---

<!-- TOC --><a name="theorem-5-relationship-between-one-sided-and-two-sided-limits"></a>
### **Theorem 5: Relationship Between One-Sided and Two-Sided Limits**

**Formal Version:**
A two-sided limit exists **if and only if** both the left-hand and right-hand limits exist **and are equal**.

$$
\lim_{x \to a} f(x) = L  
\quad \text{if and only if} \quad  
\lim_{x \to a^-} f(x) = L = \lim_{x \to a^+} f(x)
$$

---

**Plain English Explanation:**

To say the limit of a function exists at a point, you **must** check from both sides:

* If both sides approach the **same number**, the full limit exists and equals that number.
* If they approach **different numbers** (or one side doesn’t exist), then the full limit **does not exist**.

**Example:**
Using the same piecewise function as earlier:

$$
f(x) = 
\begin{cases}
1, & x < 0 \\
2, & x > 0
\end{cases}
$$

* Left-hand limit = 1
* Right-hand limit = 2
  → Two-sided limit **does not exist**



<!-- TOC --><a name="continuity"></a>
## **Continuity**



<!-- TOC --><a name="basic-terms"></a>
### **Basic Terms**

* A function is **continuous** if you can draw its graph **without lifting your pencil**.
* More formally, a function is continuous at a point if the limit at that point **exists**, the function is **defined** there, and the two are **equal**.

---

<!-- TOC --><a name="continuity-at-a-point"></a>
### **Continuity at a Point**

For a function to be **continuous at $x = a$**, three things must be true:

1. $f(a)$ is defined.
2. $\lim_{x \to a} f(x)$ exists.
3. $\lim_{x \to a} f(x) = f(a)$

If any of these are missing, the function is **not** continuous at that point.

---

<!-- TOC --><a name="removable-discontinuity"></a>
#### **Removable Discontinuity**

* A "hole" in the graph.
* The limit exists, but the function is either not defined there or is defined to the wrong value.

**Example:**

$$
f(x) = \frac{x^2 - 1}{x - 1}
$$

This simplifies to $f(x) = x + 1$ for $x \neq 1$, but there's a **hole at $x = 1$** because the original function was undefined there.

---

<!-- TOC --><a name="jump-discontinuity"></a>
#### **Jump Discontinuity**

* The left and right limits exist, but they are **not equal**.
* You see a "jump" in the graph.

**Example:**
Piecewise functions that switch values at a certain point often have jump discontinuities.

---

<!-- TOC --><a name="infinite-discontinuity"></a>
#### **Infinite Discontinuity**

* The function heads toward **infinity** at the point.
* Often seen with vertical asymptotes.

**Example:**

$$
f(x) = \frac{1}{x - 2}
$$

As $x \to 2$, the function becomes infinitely large or small.

---

<!-- TOC --><a name="continuous-at-a-left-or-right-endpoint"></a>
#### **Continuous at a Left or Right Endpoint**

If a function is only defined from one side (like an interval that starts at a certain point), we can only check **one-sided continuity**.

* **Left endpoint:** use the **right-hand limit**.
* **Right endpoint:** use the **left-hand limit**.

**If the one-sided limit equals the function value, it’s continuous at that endpoint.**

---

<!-- TOC --><a name="continuity-on-intervals"></a>
#### **Continuity on Intervals**

A function is continuous on an interval if it is continuous **at every point** in that interval.

* Open interval $(a, b)$: function must be continuous between the two ends.
* Closed interval $[a, b]$: function must also be continuous **at the endpoints**, using one-sided limits.

---

<!-- TOC --><a name="key-theorems-about-continuity"></a>
## **Key Theorems About Continuity**

---

<!-- TOC --><a name="theorem-6-continuity-of-algebraic-combinations"></a>
### **Theorem 6: Continuity of Algebraic Combinations**

**Plain English Explanation:**
If two functions are continuous at a point, then you can:

* **Add**, **subtract**, **multiply**, or **divide** them (except dividing by 0),
* And the result will also be continuous at that point.

**Example:**
If $f(x)$ and $g(x)$ are continuous at $x = 2$, then so is $f(x) + g(x)$, $f(x)g(x)$, etc.

---

<!-- TOC --><a name="theorem-7-continuity-of-polynomials-and-rational-functions"></a>
### **Theorem 7: Continuity of Polynomials and Rational Functions**

**Plain English Explanation:**

* **Polynomials** (like $x^2 + 3x - 1$) are continuous **everywhere**.
* **Rational functions** (fractions made of polynomials) are continuous **wherever the denominator isn’t zero**.

**Example:**

$$
f(x) = \frac{x^2 - 1}{x - 2}
$$

This is continuous everywhere **except** $x = 2$, where it’s undefined.

---

<!-- TOC --><a name="theorem-8-continuity-of-composite-functions"></a>
### **Theorem 8: Continuity of Composite Functions**

**Plain English Explanation:**

If:

* $g(x)$ is continuous at $x = a$,
* $f(x)$ is continuous at $g(a)$,

Then the composition $f(g(x))$ is **also continuous at $x = a$**.

**Example:**
If $f(x) = \sin x$ and $g(x) = x^2$, then $f(g(x)) = \sin(x^2)$ is continuous because both parts are continuous.

---

<!-- TOC --><a name="theorem-9-the-intermediate-value-theorem-ivt"></a>

### **Theorem 9: The Intermediate Value Theorem (IVT)**

**Plain English Explanation:**

If a function is continuous on a closed interval $[a, b]$, and the function takes on values $f(a)$ and $f(b)$, then it must **hit every value between $f(a)$ and $f(b)$** somewhere in that interval.

This means the function **can’t skip over** any value—it has to pass through all of them.

**Why it matters:**
The IVT is used to **prove that equations have solutions**. If $f(a)$ is negative and $f(b)$ is positive, there must be some point where $f(x) = 0$.

**Example:**
If $f(1) = -3$ and $f(4) = 5$, and $f$ is continuous, then **somewhere between 1 and 4**, the function equals 0.

---

