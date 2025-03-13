## 1.5 Factoring Polynomials
#### Factoring the Greatest Common Factor of a Polynomial
- **Greatest common factor** of two numbers is the largest number that divides evenly into both numbers (ex: 4 is the GCF of 16 and 20). When factoring a polynomial expression, the first step should be to check for a GCF, in this instance, the largest polynomial that divides evenly into the polynomials
- Example 1.1: $6x^3y^3 + 45x^2y^2 + 21xy$
  - GCF of 6, 45, and 21 is 3
  - GCF of $x^3$, $x^2$, and $x$ is $x$ and GCF of $y^3$, $y^2$ and $y$ is $y$
    - Note that the GCF of a set of expressions in the form $x^n$ will always be the exponent of lowest degree
  - Determine what the GCF needs to be multiplied by to obtain each term of the polynomial
    - $3xy(2x^2y^2) = 6x^3y^3$
    - $3xy(15xy) = 45x^2y^2$
    - $3xy(7) = 21xy$
  - Finally, write the factored expression as a product of the GCF and sum of the terms
    - $3xy(2x^2y^2 + 15xy + 7)$
- Example 1.2: $x(b^2 - a) + 6(b^2 - a)$
  - $(b^2 - a)(x + 6)$
#### Factoring a Trinomial with Leading Coefficient 1
- You should always begin by looking for a GCF, but extracting the GCF is not the only way a polynomial can be factored
  - For example, $x^2 + 5x + 6$ can be refactored as $(x + 2)(x + 3)$
- Trinomials in the form of $x^2 + bx + c$ can be factored by finding two numbers with a product of $c$ and a sum of $b$
  - Example: $x^2 + 10x + 16$ can be factored using 2 and 8. Then it can be rewritten as $(x + 2)(x + 8)$
- Trinomials that cannot be factored as a product of binomials are said to be prime
- Example 2.1: $x^2 + 2x - 15$
  - $(x - 3)(x + 5)$
- Example 2.2: $x^2 - 7x + 6$
  - $(x - 6)(x - 1)$
#### Factoring by Grouping
- Trinomials with leading coefficients other than 1 are slightly more complicated, but can be factored by grouping by dividing the x term into the sum of two terms, factoring each portion of the expression, then factoring out the GCF of the entire expression
- Example: $2x^2 + 5x + 3 = 2x^2 + 2x + 3x + 3 = 2x(x + 1) + 3(x + 1) = (x + 1)(2x + 3)$
- To factor $ax^2 + bx + c$, find two numbers with a product of $ac$ and a sum of $b$. Use these numbers to divide the $x$ term into the sum of two terms, factor each portion of the expression separately, then factor out the GCF of the entire expression
- Example 3.1: $5x^2 + 7x - 6$
  - Find factors of $ac$, in this instance $5 \cdot -6 = -30$ that sum to 7. In this instance, these will be -3 and 10
  - $5x^2 - 3x + 10x - 6 = (5x^2 - 3x) + (10x - 6)$
  - $x(5x - 3) + 2(5x - 3)$
  - $(5x - 3)(x + 2)$
#### Factoring a Perfect Square Trinomial
- A perfect square trinomial is one that can be written as the square of a binomial
- First, you need to confirm that first and last term are perfect squares, the confirm the middle term is twice the product of $ab$, then write the factored form as $(a + b)^2$
- Example 4.1: $25x^2 + 20x + 4$
  - $25x^2$ is a perfect square of $5x$, and 4 is a perfect square of 2
  - Twice the product of $5x$ and $2$ ($10x$) is $20x$
  - Therefore, this trinomial is a perfect square trinomial
  - $(5x + 2)^2$
- Example 4.2: $49x^2 - 14x + 1$
  - $7x$ and $-1$
  - $7x \cdot -1 = -7x$ multiplied by 2 is $-14x$
  - $(7x - 1)^2$
#### Factoring a Difference of Squares
- A difference of squares is a perfect square subtracted from a perfect square. Remember that the difference of squares can be rewritten as factors containing the same terms, but with opposite signs (as the middle terms cancel each other out)
- Example form: $a^2 - b^2 = (a + b)(a - b)$
- Example 5.1: $9x^2 - 25$
  - $(3x + 5)(3x - 5)$
- Example 5.2: $81y^2 - 100$
  - $(9y + 10)(9y - 10)$
#### Factoring the Sum and Difference of Cubes
- The sum of cubes can be factored into a binomial and a trinomial
  - Example form: $a^3 + b^3 = (a + b)(a^2 - ab + b^2)$
- The difference of cubes can also be factored into a binomial and trinomial, but with different signs
  - Example form: $a^3 - b^3 = (a + b)(a^2 + ab + b^2)$
- You can use the acronym *SOAP* to remember the signs when factoring sum/difference of cubes
  - **SOAP**: **S**ame **O**pposite **A**lways **P**ositive
  - Example: $x^3 - 2^3 = (x - 2)(x^2 + 2x + 4)$
  - The sign on the first 2 is the *same* as the sign between $x^3 - x^3$, the sign of the $2x$ term is *opposite* the sign between $x^3 - 2^3$, the sign of the last term, 4, is *always positive*
- Example 6.1: $x^3 + 512$
  - $(x + 8)(x^2 - 8x + 64)$
- Example 6.2: $216a^3 + b^3$
  - $(6a + b)(36a^2 - 6ab + b^2)$
- Example 7.1: $8x^3 - 125$
  - $(2x - 5)(4x^2 + 10x + 25)$
- Example 7.2: $1000x^3 - 1$
  - $(10x - 1)(100x^2 + 10x + 1)$
#### Factoring Expressions with Fractional or Negative Exponents
- Expressions with fractional or negative exponents can be factored by pulling out a GCF. Look for the variable or exponent that is common to each term of the expression and pull out that variable or exponent raised to the lowest power. These follow the same factoring rules as integer exponents
  - For example, $2x^{\frac{1}{4}} + 5x^{\frac{3}{4}}$ can be factored by pulling out $x^{\frac{1}{4}}$ and then being rewritten as $x^{\frac{1}{4}}(2 + 5x^{\frac{1}{2}})$
- Example 8.1: $3x(x + 2)^{-\frac{1}{3}} + 4(x + 2)^{\frac{2}{3}}$
  - Factor out GCF $(x + 2)^{-\frac{1}{3}}(3x + 4(x + 2))$
  - Simplify $(x + 2)^{-\frac{1}{3}}(3x + 4x + 8)$
  - $(x + 2)^{-\frac{1}{3}}(7x + 8)$
- Example 8.2: $2(5a - 1)^{\frac{3}{4}} + 7a(5a - 1)^{-\frac{1}{4}}$
  - Factor out GCF $(5a - 1)^{-\frac{1}{4}}(2 + 7a(5a - 1))$
  - $(5a - 1)^{-\frac{1}{4}}(2 + 7a)$
