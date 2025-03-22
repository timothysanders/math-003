## 2.6: Other Types of Equations
### Solving Equations Involving Rational Exponents
- Rational exponents are exponents that are fractions, where the numerator is a power and the denominator is a root. For example, $16^\frac{1}{2}$ is the same as writing $\sqrt{16}$; $8^\frac{1}{3}$ is the same as $\sqrt[3]{8}$
- Rational equations can be solved by raising both sides of the equation to the reciprocal of the exponent. This is because we want to eliminate the exponent on the variable term, and a number multiplied by its reciprocal equals 1.
##### Rational Exponents
- A rational exponent indicates a power in the numerator and a root in the denominator. There are multiple ways of writing an expression, a variable, or a number with a rational exponent
  - $a^\frac{m}{n} = (a^\frac{1}{n})^m = (a^m)^\frac{1}{n} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m$
##### Examples
- Evaluate $8^\frac{2}{3}$
  - $8^\frac{2}{3} = (8^\frac{1}{3})^2 = (\sqrt[3]{8})^2 = 2^2 = 4$
- Evaluate $64^{-\frac{1}{3}}$
  - $\frac{1}{64^\frac{1}{3}} = \frac{1}{\sqrt[3]{64}} = \frac{1}{4}$
- Solve $x^\frac{5}{4} = 32$
  - The key step here is to remove the exponent of $x$ by raising both sides to a power that is the reciprocal of $\frac{5}{4}$, which is $\frac{4}{5}$
  - $(x^\frac{5}{4})^\frac{4}{5} = 32^\frac{4}{5}$
  - $x = \sqrt[5]{32}^4$
  - $x = 2^4 = 16$
- Solve $x^\frac{3}{2} = 125$
  - $(x^\frac{3}{2})^\frac{2}{3} = 125^\frac{2}{3}$
  - $x = \sqrt[3]{125}^2$
  - $x = 5^2 = 25$
### Solving Equations Using Factoring
- Factoring can be used for many types of polynomial equations. When we have an equation of a degree higher than 2, we can often solve by factoring
##### Polynomial Equations
- A polynomial of degree $n$ is an expression of the type
  - $a_nx^n + a_{n-1}x^{n - 1}+ \cdot \cdot \cdot + a_2x^2 + a_1x + a_0$
- where $n$ is a positive integer and $a_n, ... , a_0$ are real numbers and $a_n \ne 0$
- Setting the polynomial equal to zero gives a **polynomial equation**. The total number of solutions (real and complex) to a polynomial equation is equal to the highest exponent $n$.
##### Examples
- Solve by factoring: $5x^4 = 80x^2$
  - $5x^4 - 80x^2 = 0$
  - $5x^2(x^2 - 16) = 0$
  - $5x^2(x + 4)(x - 4) = 0$
  - $5x^2 = 0; x = 0$ (double solution)
  - $x + 4 = 0; x = -4$
  - $x - 4 = 0; x = 4$
- Solve by grouping: $x^3 + x^2 - 9x - 9 = 0$
  - Factor the first two terms and factor the last two terms
  - $(x^3 + x^2) - (9x - 9) = 0$
  - $x^2(x + 1) - 9(x + 1) = 0$
  - $(x^2 - 9)(x + 1) = 0$
  - Need to continue factoring the difference of squares
  - $(x - 3)(x + 3)(x + 1) = 0$
  - $x - 3 = 0; x = 3$
  - $x + 3 = 0; x = -3$
  - $x = -1$
### Solving Radical Equations
- **Radical equations** are equations that contain variables in the radicand (the expression under a radical symbol). These equations may have more than one term, and are solved by eliminating each radical, one at a time. We have to be careful here, because there are sometimes **extraneous solutions**, roots that are not solutions to the equation. Therefore, we need to double-check our answers
  - $\sqrt{3x + 18} = x$
  - $\sqrt{x + 3} = x - 3$
  - $\sqrt{x + 5} - \sqrt{x - 3} = 2$
##### Radical Equations
- An equation containing terms with a variable in the radicand is called a **radical equation**
##### How To
- Given a radical equation, solve it
  1. Isolate the radical expression on one side of the equal sign. Put all remaining terms on the other side
  2. If the radical is a square root, then square both sides of the equation. If it is a cube root, then raise both sides of the equation to the third power. In other words, for an nth root radical, raise both sides to the nth power. Doing so eliminates the radical symbol.
  3. Solve the remaining equation
  4. If a radical term still remains, repeat steps 1-2
  5. Confirm solutions by substituting them into the original equation
##### Examples
- Solve: $\sqrt{15 - 2x} = x$
  - $\sqrt{15 - 2x}^2 = x^2$
  - $15 - 2x = x^2$
  - $x^2 + 2x - 15 = 0$
  - $(x + 5)(x - 3) = 0$
  - $x = -5$
  - $x = 3$
  - Double check: $\sqrt{15 - 2(-5)} = -5$
    - $5 \ne -5$
  - Double check: $\sqrt{15 - 2(3)} = 3$
    - $\sqrt{9} = 3$
- Solve: $\sqrt{x + 3} = 3x - 1$
  - $x + 3 = (3x - 1)^2$
  - $(3x - 1)(3x - 1)$
  - $9x^2 - 3x - 3x + 1 = x + 3$
  - $9x^2 - 7x - 2 = 0$
    - Factor by grouping: $9 \cdot -2 = -18$
  - $9x^2 - 9x + 2x - 2 = 0$
  - $9x(x - 1) + 2(x - 1) = 0$
  - $(9x + 2)(x - 1) = 0$
  - $9x + 2 = 0$
    - $x = -\frac{2}{9}$
  - $x = 1$
  - Double check: $\sqrt{1 + 3} = 3(1) - 1$
    - $2 = 2$
  - Double check: $\sqrt{-\frac{2}{9} + 3} = 3(-\frac{2}{9}) - 1$
    - $\sqrt{\frac{25}{9}} = \frac{5}{3}$
    - $3(-\frac{2}{9}) - 1 = -\frac{6}{9} = -\frac{2}{3} - 1 = -\frac{5}{3}$
    - $\frac{5}{3} \ne -\frac{5}{3}$
- $\sqrt{3x + 7} + \sqrt{x + 2} = 1$
### Solving an Absolute Value Equation
- To solve absolute value equations, such as $|2x - 6| = 8$, we need to keep in mind that the absolute value could be positive or negative, in this instance 8 or -8
  - Example: $2x - 6 = 8$
    - $2x = 14$
    - $x = 7$
  - Example: $2x - 6 = -8$
    - $2x = -2$
    - $x = -1$
##### Absolute Value Equations
- The absolute value of $x$ is written as $|x|$. It has the following properties
  - If $x \geq 0$, then $|x| = x$
  - If $x \lt 0$, then $|x| = -x$
- For real numbers $A$ and $B$, an equation of the form $|A| = B$, with $B \geq 0$, will have solutions when $A = B$ or $A = -B$. If $B \lt 0$, the equation $|A| = B$ has no solution
- An **absolute value equation** in the form $|ax + b| = c$ has the following properties.
  - If $c \lt 0$, $|ax + b| = c$ has no solution
  - If $c = 0$, $|ax + b| = c$ has one solution
  - If $c \gt 0$, $|ax + b| = c$ has two solutions
##### How To
- Given an absolute value equation, solve it
  1. Isolate the absolute value expression on one side of the equal sign
  2. If $c \gt 0$, write and solve two equations: $ax + b = c$ and $ax + b = -c$
##### Examples
- $|6x + 4| = 8$
- $|3x + 4| = -9$
- $|3x - 5| -4 = 6$
- $|-5x + 10| = 0$
- $|1 - 4x| + 8 = 13$
### Solving Other Types of Equations
#### Solving Equations in Quadratic Form
- **Equations in quadratic form** are equations with three terms, the first with a power other than 2, the middle term has an exponent that is one-half the exponent of the leading term, and the third term is a constant
  - Example: $x^4 - 5x^2 + 4 = 0$, $x^6 + 7x^3 - 8 = 0$, etc.
- In these equations, we can solve these by substituting a variable for the middle term
##### Quadratic Form
- If the exponent on the middle term is one-half the exponent on the leading term, we have an **equation in quadratic form**, which we can solve as if it were quadratic. We substitute a variable for the middle term to solve equations in quadratic form
##### How To
- Given an equation quadratic in form, solve it
  1. Identify the exponent on the leading term and determine whether it is double the exponent on the middle term
  2. If it is, substitute a variable, such as $u$, for the variable portion of the middle term
  3. Rewrite the equation so that it takes on the standard form of a quadratic
  4. Solve using one of the usual methods for solving a quadratic
  5. Replace the substitution variable with the original term
  6. Solve the remaining equation
#### Solving Rational Equations Resulting in a Quadratic
- When we solve a rational equation that results in a quadratic, we continue the solving by simplifying the quadratic equation
- Example: $\frac{-4x}{x + 1} + \frac{4}{x + 1} = \frac{-8}{x:^2 - 1}$
  - Find LCD: $(x + 1)(x - 1)$
  - Multiply both sides by LCD and cancel terms
    - $-4x^2 + 4x - 4x - 4 = -8$
    - $-4x^2 + 8x + 4 = 0$
    - $-4x^2 + 4 = 0$
    - $-4(x^2 - 1) = 0$
    - $-4(x - 1)(x + 1) = 0$
    - $x = 1$
    - $x - 1$
  - Both solutions produce a zero in the initial equation, so there is no solution


---
In-class notes
- $(32)^\frac{3}{5} = \sqrt[5]{32^2}$
  - $(2^5)^\frac{3}{5} = 2^{5 \cdot \frac{3}{5}} = 2^3 = 8$
- $x^{\frac{2}{3}} = 64$
  - $(x^{\frac{2}{3}})^{\frac{3}{2}} = (64)^{\frac{3}{2}}$
  - $x^1 = (8^2)^{\frac{3}{2}}$
  - $x = 8^3 = 512$
- $x^{\frac{3}{2}} = \sqrt[2]{x^3}$
- $(x + 5)^{\frac{3}{2}} = 8$
  - $((x + 5)^{\frac{3}{2}})^{\frac{2}{3}} = 8^{\frac{2}{3}}$
  - $(x + 5) = (2^3)^{\frac{2}{3}} = 4$
- $\sqrt{15 - 2x} = x$
  - First step to get rid of the radical is square both sides
  - $15 - 2x = x^2$
  - $0 = x^2 + 2x - 15$
  - $(x + 5)(x - 3) = 0$
  - $x = -5; x = 3$
  - **YOU MUST CHECK THE ANSWERS FOR RADICAL EQUATIONS**, because when you square your answer, you may be getting extraneous answers. Go to original equation and plug in your answers
  - $\sqrt{15 - 2(-5)} = (-5)$
  - $\sqrt{15 - 2(3)} = 3$
    - $\sqrt{9} = 3$ is True
- $\sqrt{x + 3} = 3x - 1$
  - Square both sides
  - $x + 3 = (3x - 1)^2$
  - $x + 3 = 9x^2 - 6x + 1$
  - $9x^2 - 7x - 2 = 0$
  - $(9x + 2)(x - 1) = 0$
    - $x = \frac{-2}{9}$
    - $x = 1$
  - Check: $x = \frac{-2}{9}$
  - Check: $x = 1$
- $\sqrt{x - 1} = x - 7$
  - Square both sides
  - $x - 1 = (x - 7)^2$
    - $(a - b)^2 = a^2 - 2ab + b^2$
    - $x^2 - 14x + 49$
  - $x - 1 = x^2 - 14x + 49$
  - $0 = x^2 - 15x + 50$
  - $(x - 10)(x - 5) = 0$
  - x = 10
  - x = 5
  - Check answers
    - $\sqrt{5 - 1} = 5 - 7$
      - $2 \ne -2$
    - $\sqrt{10 - 9} = 10 - 7$
      - $3 = 3$
- If you see repeating items, such as $(x + 1)$, substitute something like $y$
  - $(x + 1)^2 - 8(x + 1) - 9 = 0$
  - substitution: $y^2 - 8y - 9 = 0$ then factor
  - $(y + 2)(y + 1) = 0$
  - $y = -2; y = -1$
  - substitute back: $x - 1 = -2; x - 1 = -1$
    - $x = -1; x = 0$
- $(x - 1)^2 + 3(x + 2) + 2 = 0$
  - Drop parentheses and start over
  - $x2 + x + 9 = 0$
- $(x + 1)^6 - 7(x + 1)^3 - 8 = 0$
  - Substitute $y$ for $(x + 1)^3$
  - $y^2 - 7y - 8 = 0$
  - $(y - 8)(y + 1) = 0$
  - $y = 8; y = -1$
  - Resubstitute: $(x + 1)^3 = 8; (x + 1)^3 = -1$
    - $\sqrt[3]{(x + 1)^3} = \sqrt[3]{8}$
    - $x + 1 = 2$
    - $x = 1$
    - $\sqrt[3]{(x + 1)^3} = \sqrt[3]{-1}$
    - $x = -2$
- If a quadratic equation is not factorable, use the quadratic formula to solve
  - **NEED TO KNOW THE QUADRATIC FORMULA BY HEART**
- $\frac{2x - 1}{x + 1} - 3 = \frac{x}{x^2 - 1}$
  - When you have a rational equation, you see fractions with variables in the denominator. If it does not have variables in the denominator, it **IS NOT** a rational equation
  - Because you have a variable, you have an unknown in the denominator. Dividing by zero is not allowed, so you need to have restrictions
    - Restrictions: $x \ne -1; x \ne \pm 1$
  - In equations, you can clear the denominator, in expressions you cannot clear the denominator
  - $\frac{2x - 1}{x + 1} - 3 = \frac{x}{(x + 1)(x - 1)}$
  1. Factor all denominators
  2. Based on factored denominators, state restrictions (exclude numbers that turn denominators into zero)
  3. Find LCD
  4. Multiply each term (whether it has the LCD denominator or not) by LCD (only numerators)
  5. Solve the resulting equation
  - $(x - 1)(2x - 1) - 3(x + 1)(x - 1) = x$
    - Remove the parentheses and start over
    - $2x^2 - 2x - x + 1 - 3x^2 + 3 = x$
    - $-x^2 - 4x + 4 = 0$ -> $x^2 + 4x - 4 = 0$
      - This is not factorable, so we use the quadratic formula
      - $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
      - $x = \frac{-4 \pm \sqrt{4^2 -4 \cdot 1 \cdot (-4)}}{2 \cdot 1}$
      - $x = \frac{-4 \pm 4\sqrt{2}}{2}$
      - $x = -2 \pm 2\sqrt{2}$
- When working with an absolute value equation/inequality, there are four outcomes
  1. $|x| = a, a \geq 0$
    - $x = a; x = -a$
    - For example $|x| = 2; x = 2; x = -2$
    - Need to isolate the absolute value
      - Ex: $3|5x - 7| - 2 = 1$ = $|5x - 7| = 1$
      - $5x - 7 = 1; x = \frac{8}{5}$ or $5x - 7 = -1; x = \frac{6}{5}$
    - 
  - $|x| = b; b \lt 0$
    - stop, do not branch out, there is no solution
  2. $|x| = |y|$
    - This happens only if the two numbers are identical
    - $x = y$  or $x = -y$
    - $x + 3 = 2x - 1$ or $x + 3 = -(2x - 1)$
    - $4 = x$ or $x = \frac{-2}{3}$
  3. $|x| < a$
    - $-a \lt x \lt a$
    - $-3|2x - 1| + 5 \gt -1$
    - $|2x - 1| \lt 2$
    - $-2 \lt 2x - 1 \lt 2$
      - $\frac{-1}{2} \lt x \lt \frac{3}{2}$
  4. $|x| \gt a$
    - If you have $|x| \lt a$ and $a$ is a negative number, stop and do not continue, write "no solution"
      - The absolute value has to be all alone
    - $x \gt a$ or $x \lt -a$
    - Drop the absolute value bars, but don't forget that every absolute value statement ends up in two smaller equations
    - $|x| \gt -2$
      - Stop and write "all real numbers" as the absolute value of every number is greater than a negative
    - $\frac{-1}{3}|x - 2| < -5$
      - Multiply by the reciprocal of the fraction
      - $|x - 2| \gt 15$
      - $x - 2 \gt 15$ or $x - 2 \lt -15$
      - $x \gt 17$ or $x \lt -13$