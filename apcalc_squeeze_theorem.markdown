# Introduction
Hello everyone, welcome to the Karu lesson on "Determining Limits using the Squeeze Theorem". In calculus, a limit is an important concept that describes the behavior of a function near a point. The squeeze theorem, also known as the sandwich theorem or the pinching theorem, is a powerful tool that allows us to determine the limit of a function by "squeezing" it between two other functions whose limits are known. 

# Sections
## Section 1: Understanding the Squeeze Theorem
The squeeze theorem states that if a function f(x) is squeezed between two other functions g(x) and h(x) such that g(x) ≤ f(x) ≤ h(x) for all x in some interval except possibly at x = a, where a is the point of interest, and if lim g(x) = L = lim h(x), then lim f(x) also exists and is equal to L.

In simpler terms, if we can find two simpler functions that sandwich our function f(x) such that they both approach the same limit L, then f(x) must also approach that same limit L. This is illustrated in the following equation:

$$ g(x) \leq f(x) \leq h(x) $$
$$ \lim_{x \to a} g(x) = \lim_{x \to a} h(x) = L $$
$$ \implies \lim_{x \to a} f(x) = L $$

It is important to note that the squeeze theorem only works when the two functions g(x) and h(x) are "squeezing" f(x) from both sides. In other words, g(x) must always be less than or equal to f(x), while h(x) must always be greater than or equal to f(x).

## Section 2: Solving Limit Problems using the Squeeze Theorem
To use the squeeze theorem to solve limit problems, we first need to identify a function f(x) that is difficult to evaluate using algebraic methods. We can then use the squeeze theorem to "squeeze" f(x) between two simpler functions whose limits we can evaluate. 

Let's take a look at an example:

**Example 1:** Evaluate the limit of the function  f(x) = xsin(1/x) as x approaches 0.

Solution: 

First, we notice that evaluating the limit directly is difficult because the function is not defined at x = 0. However, by applying the squeeze theorem, we can find the limit.

We know that -1 ≤ sin(1/x) ≤ 1 for all x ≠ 0. Therefore, we can "squeeze" f(x) as follows:

$$ -x \leq x\sin(\frac{1}{x}) \leq x $$

Taking the limit as x approaches 0 of both sides of the inequality, we get:

$$ \lim_{x \to 0} (-x) = 0 = \lim_{x \to 0} x $$

Therefore, by the squeeze theorem, we can conclude that:

$$ \lim_{x \to 0} x\sin(\frac{1}{x}) = 0 $$

## Section 3: Common Mistakes to Avoid
There are a few common mistakes that students make when using the squeeze theorem.

The first mistake is forgetting to check that the two functions g(x) and h(x) actually do "squeeze" f(x) from both sides. It is important to always check that g(x) ≤ f(x) ≤ h(x) for all x in the interval except possibly at x = a.

The second mistake is forgetting to identify the simpler functions g(x) and h(x) that we can use to "squeeze" the function f(x). It is important to identify these functions before applying the squeeze theorem.

The third mistake is forgetting to take the limit of both simpler functions g(x) and h(x). It is important to evaluate both limits to ensure that they are equal.

## Section 4: Example Problems
**Example 2:** Evaluate the limit of the function f(x) = $x^2 \cos(\frac{1}{x})$ as x approaches 0.

Solution:

We know that -1 ≤ cos(1/x) ≤ 1 for all x ≠ 0. Therefore, we can "squeeze" f(x) as follows:

$$ -x^2 \leq x^2 \cos(\frac{1}{x}) \leq x^2 $$

Taking the limit as x approaches 0 of both sides of the inequality, we get:

$$ \lim_{x \to 0} (-x^2) = 0 = \lim_{x \to 0} x^2 $$

Therefore, by the squeeze theorem, we can conclude that:

$$ \lim_{x \to 0} x^2 \cos(\frac{1}{x}) = 0 $$

**Example 3:** Evaluate the limit of the function f(x) = $x\sin(\frac{1}{x^2})$ as x approaches 0.

Solution:

We know that -1 ≤ sin(1/x^2) ≤ 1 for all x ≠ 0. Therefore, we can "squeeze" f(x) as follows:

$$ -x \leq x\sin(\frac{1}{x^2}) \leq x $$

Taking the limit as x approaches 0 of both sides of the inequality, we get:

$$ \lim_{x \to 0} (-x) = 0 = \lim_{x \to 0} x $$

Therefore, by the squeeze theorem, we can conclude that:

$$ \lim_{x \to 0} x\sin(\frac{1}{x^2}) = 0 $$

# Conclusion
The squeeze theorem is a powerful tool that allows us to determine the limit of a function by "squeezing" it between two other functions whose limits are known. It is important to always check that the two functions g(x) and h(x) actually do "squeeze" f(x) from both sides, to identify the simpler functions g(x) and h(x) that we can use to "squeeze" the function f(x), and to take the limit of both simpler functions g(x) and h(x). By applying the squeeze theorem correctly, we can evaluate the limit of difficult functions that are otherwise hard to evaluate using algebraic methods.

