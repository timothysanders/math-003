## 1.6 Rational Expressions
#### Simplifying Rational Expressions
- The quotient of two polynomial expressions is called a **rational expression** and properties of fractions can be applied to these, such as simplifying by canceling common factors. The first step is to factor the numerator and the denominator
- $\frac{x^2 + 8x + 16}{x^2 + 11x + 28}$
  - After factoring the numerator and the denominator, we get $\frac{(x + 4)^2}{(x + 4)(x + 7)}$
  - Then, we can simplify by canceling the common factor $(x + 4)$ to get $\frac{x + 4}{x + 7}$
- Example 1: simplify $\frac{x^2 - 9}{x^2 + 4x + 3}$
  - After factoring, we get $\frac{(x + 3)(x - 3)}{(x + 3)(x + 1)}$
  - Cancel out the common factor $(x + 3)$ and we get $\frac{x - 3}{x + 1}$
- Example 1.1: simplify $\frac{x - 6}{x^2 - 36}$
  - After factoring, we get $\frac{x - 6}{(x + 6)(x - 6)}$
  - Cancel the common factor $(x - 6)$ and we get $\frac{1}{x + 6}$
#### Multiplying Rational Expressions
- Multiplying rational expressions works like multiplication of any other fractions, where you multiply the numerator, then multiply the denominator. Before multiplying, you can factor the numerator/denominator to simplify the expressions
- Example 2: Multiply $\frac{x^ + 4x - 5}{3x + 18} \cdot \frac{2x - 1}{x + 5}$
  - After factoring, we get $\frac{(x - 1)(x + 5)}{3(x + 6)} \cdot \frac{2x - 1}{x + 5}$
  - Cancel out $x + 5$, then we get $\frac{(x - 1)(2x - 1)}{3(x + 6)}$
- Example 2.1: simplify $\frac{x^2 + 11x + 30}{x^2 + 5x + 6} \cdot \frac{x^2 + 7x + 12}{x^2 + 8x + 16}$
  - After factoring, we get $\frac{(x + 5)(x + 6)}{(x + 3)(x + 2)} \cdot \frac{(x + 4)(x + 3)}{(x + 4)^2}$
  - Cancel out common factors, we are left with $\frac{(x + 5)(x + 6)}{(x + 2)(x + 4)}$
#### Dividing Rational Expressions
- Dividing rational expressions works the same as division of other fractions, where you multiply the first expression by the reciprocal of the second, so $\frac{1}{x} \div \frac{x^2}{3}$ becomes $\frac{1}{x} \cdot \frac{3}{x^2} = \frac{3}{x^3}$
- **How to**
  1. Rewrite as the first rational expression multiplied by the reciprocal of the second
  2. Factor the numerators and denominators
  3. Multiply the numerators
  4. Multiply the denominators
  5. Simplify
- Example 3: divide and express in simplest form $\frac{2x^2 + x - 6}{x^2 - 1} \div \frac{x^2 - 4}{x^2 + 2x + 1}$
  - Change to multiplication by reciprocal $\frac{2x^2 + x - 6}{x^2 - 1} \cdot \frac{x^2 + 2x + 1}{x^2 - 4}$
  - After factoring, we get $\frac{(2x - 3)(x + 2)}{(x + 1)(x - 1)} \cdot \frac{(x + 1)^2}{(x + 2)(x - 2)}$
  - Cancel common factors, we are left with $\frac{(2x - 3)(x + 1)}{(x - 1)(x - 2)}$
- Example 3.1
#### Adding and Subtracting Rational Expressions
- Adding and subtracting rational expressions works just like adding and subtracting numerical fractions. To add fractions, we need a common denominator, so we should try to find the **least common denominator** (LCD), the smallest multiple the denominators have in common. For a rational expression, factor the expressions and multiply all the distinct factors. For example, if the factored denominators were $(x + 3)(x + 4)$ and $(x + 4)(x + 5)$, the LCD would be $(x + 3)(x + 4)(x + 5)$. After finding the LCD, need to multiply each expression by the form of 1 that will change denominator to LCD. Using our previous example, we would multiply $(x + 3)(x + 4) \cdot \frac{x + 5}{x + 5}$ and $(x + 4)(x + 5) \cdot \frac{x + 3}{x + 3}$
- **How to**
  1. Factor the numerator and the denominator
  2. Find the LCD of the expressions
  3. Multiply the expressions by a form of 1 that changes the denominators to the LCD
  4. Add or subtract the numerators
  5. Simplify
- Example 4: $\frac{5}{x} + \frac{6}{y}$
  - Find the LCD, in this instance $xy$ and multiply to make each denominator equal to the LCD
  - $\frac{5}{x} \cdot \frac{y}{y} + \frac{6}{y} \cdot \frac{x}{x} = \frac{5y}{xy} + \frac{6x}{xy}$
  - Add numerators $\frac{6x + 5y}{xy}$
- Example 5: $\frac{6}{x^2 + 4x + 4} - \frac{2}{x^2 - 4}$
  - Factor: $\frac{6}{(x + 2)^2} - \frac{2}{(x + 2)(x - 2)}$
  - Find the LCD, in this instance, $(x + 2)^2(x -2)$
  - Multiply denominators to get LCD $\frac{6}{(x + 2)^2} \cdot \frac{x - 2}{x - 2} - \frac{2}{(x + 2)(x - 2)} \cdot \frac{x + 2}{x + 2} = \frac{6(x - 2)}{(x + 2)^2(x -2)} - \frac{2(x + 2)}{(x + 2)^2(x - 2)}$
  - Apply distributive property $\frac{6x - 12 - (2x + 4)}{(x + 2)^2(x - 2)}$
  - Subtract $\frac{4x - 16}{(x + 2)^2(x - 2)}$
  - Simplify $\frac{4(x - 4)}{(x + 2)^2(x - 2)}$
#### Simplifying Complex Rational Expressions
- A complex rational expression is a rational expression that contains additional rational expressions in the numerator/denominator/both. These can be simplified by rewriting the numerator and denominator as a single rational expression and dividing. For example, $\frac{a}{\frac{1}{b} + c}$ can be rewritten with the numerator as the fraction $\frac{a}{1}$ and combining the expressions in the denominator as $\frac{1 + bc}{b}$. Then the expression can be rewritten as a multiplication problem using the reciprocal of the denominator, $\frac{a}{1} \cdot \frac{b}{1 + bc} = \frac{ab}{1 + bc}$
- **How to**
  1. Combine the expressions in the numerator into a single rational expression by adding or subtracting
  2. Combine the expressions in the denominator into a single rational expression by adding or subtracting
  3. Rewrite as the numerator divided by the denominator
  4. Rewrite as multiplication
  5. Multiply
  6. Simplify
- Example 6: $\frac{y + \frac{1}{x}}{\frac{x}{y}}$
  - Combine expressions: $\frac{\frac{1 + xy}{x}}{\frac{x}{y}}$
  - Multiply: $\frac{1 + xy}{x} \cdot \frac{y}{x} = \frac{y(xy + 1)}{x^2}$

---
In-class notes
#### Side-by-side factoring of rational expressions
- $\frac{\frac{x}{4}-\frac{p}{8}}{p} = (\frac{x}{4}\cdot\frac{2}{2}) \div p = \frac{2x-p}{8} \cdot \frac{1}{p} = $
#### LCD Method
- $\frac{\frac{x}{4}-\frac{p}{8}}{\frac{p}{1}}$
  - Multiply by the lowest common denominator, which of 1, 4, 8 is 8
  - $\frac{8 \cdot \frac{x}{4} - \frac{p}{8} \cdot 8}{\frac{p}{1} \cdot \frac{8}{1}} = \frac{2x - p}{8p}$
  - Make sure to distinguish between Lowest Common Denominator and Greatest Common Factor
- $\frac{\frac{3}{a} + \frac{6}{b}}{\frac{2b}{3a}} = \frac{18 + ab}{4b}$
  - LCD = 6a
- $\frac{\frac{3}{x + 1} + \frac{2}{x - 1}}{\frac{x - 1}{x + 1}} = \frac{3(x - 1) + 2(x + 1)}{(x - 1)^2} = \frac{5x - 1}{(x - 1)^2}$
  - Focus on denominator, the lowest common denominator
  - Lowest common denominator: `(x+1)(x-1)`
- $\frac{\frac{x - 1}{x + 2} - \frac{x + 3}{x - 1}}{x}$
  - Denominators: x + 2
  - Move denominators into the overall denominator, then cross multiply the remaining numerator items
  - $\frac{(x - 1)(x - 1)- (x + 3)(x + 2)}{x(x + 2)(x - 1)}$
- $\frac{3x - 1}{x - 3} - \frac{x + 1}{x - 3}$
  - Because these have the same denominator, we can combine them
  - But, you need to distribute the negative
  - $\frac{3x - 1 - x - 1}{x - 3}$
- $\frac{1}{x + 1} - \frac{3}{x^2(x + 2)} - \frac{1}{x^3(x + 1)^2(x+2)} = \frac{}{(x + 1)^2x^3(x + 2)}$
  - Need to be 
