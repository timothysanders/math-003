## 2.6: Other Types of Equations
### Solving Equations Involving Rational Exponents
### Solving Equations Using Factoring
### Solving Radical Equations
### Solving an Absolute Value Equation
### Solving Other Types of Equations

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