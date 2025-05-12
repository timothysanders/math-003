## 5.7: Inverses and Radical Functions
### Finding the Inverse of a Polynomial Function
- Two functions $f$ and $g$ are inverse functions if for every coordinate pair in $f$, $(a, b)$, there exists a corresponding coordinate pair in the inverse function $g$, $(b, a)$
  - The coordinate pairs of the inverse functions have the input and output interchanged
  - Only one-to-one functions have inverses, which is a function that has a unique output value for each input value and passes the horizontal line test
- When finding the inverse of a quadratic, you need to limit the function to a domain on which the function is one-to-one
- The inverse of a quadratic is a square root function
- Functions involving roots are called radical functions
- Most polynomial functions do not have an inverse, but the ones that do are called **invertible functions**
- The notation for an inverse of a function $f(x)$ is $f^{-1}(x)$
  - Note that this is not the reciprocal of the function, which would be $\frac{1}{f(x)}$
- Important relationship between inverse functions is that they "undo" each other
  - For example, $f^{-1}(f(x)) = x$
##### Verifying Two Functions are Inverses of One Another
- Two functions, $f$ and $g$, are inverses of one another if for all $x$ in the domain of $f$ and $g$.
  - $g(f(x)) = f(g(x)) = x$
##### How To
- Given such a polynomial function, find the inverse of the function by restricting the domain in such a way that the new function is one-to-one
  1. Replace $f(x)$ with $y$
  2. Interchange $x$ and $y$
  3. Solve for $y$, and rename the function $f^{-1}(x)$
### Restricting the Domain to Find the Inverse of a Polynomial Function
- Not all cubic functions are one-to-one. For some functions that are not one-to-one, we can restrict their domain so that they are one-to-one, but only over that domain. This then allows us to have an inverse function over the restricted domain
##### Restricting the Domain
- If a function is not one-to-one, it cannot have an inverse. If we restrict the domain of the function so that it becomes one-to-one, thus creating a new function, this new function will have an inverse.
##### How To
- Given a polynomial function, restrict the domain of a function that is not one-to-one and then find the inverse
  1. Restrict the domain by determining a domain on which the original function is one-to-one
  2. Replace $f(x)$ with $y$
  3. Interchange $x$ and $y$
  4. Solve for $y$, and rename the function or pair of function $f^{-1}(x)
  5. Revise the formula for $f^{-1}(x)$ by ensuring that the outputs of the inverse function correspond to the restricted domain of the original function
#### Solving Applications of Radical Functions
- If you want to find the inverse of a radical function, you need to restrict the domain of the answer, because the range of the original function is limited
##### How To
- Given a radical function, find the inverse
  1. Determine the range of the original function
  2. Replace $f(x)$ with $y$, then solve for $x$
  3. If necessary, restrict the domain of the inverse function to the range of the original function
#### Determining the Domain of a Radical Function Composed with Other Functions
- When radical functions are composed of other functions, determining domain can become more complicated
#### Finding Inverses of Rational Functions

---
In-class notes

- Inverse function "undo" whatever was done before
  - For example, if you have $10 dollars, you get \$2, but then immediately
  - Division and multiplication are inverses of each other
    - Ex $5 \cdot 3 \div 3 = 5$
    - Ex $2^3 = 8$ and $\sqrt[3]{8} = 2$
- Inverse function can be notated as $f^{-1}$
- Inverse functions must be able to be "1 to 1"
  - For example, if you have $2^2 = 4$, the inverse is not $\sqrt{4}$, because $(-2)^2$ also equals four, so the function is not 1 to 1
  - Similar to the definition of a function, your input must lead to only one output for a function
    - "For every x, there can be only one y"
- For the original function's domain and range, the inverse function's domain is the original function's range, and the inverse function's range is the original function's domain
- After taking the inverse of a function, you should end up with the exact same original output
- Functions have to meet the "vertical line test" (vertical line only crosses the graph of a function once), but to be one to one, the function must pass the "horizontal line test" to identify functions that have an inverse
- If the function does not meet the horizontal line test, you can sometimes take the inverse, but under certain restrictions
- To find the inverse of a function, you need to switch x and y, then solve for y
- $y = \frac{1}{x + 1}$
  - $f(x) = \frac{1}{x + 1}$
  - $x = \frac{1}{y + 1}$
    - $x(y+1) = 1$
    - $xy + x = 1$
    - $xy = 1 - x$
    - $y = \frac{1-x}{x}$
    - $y = \frac{1}{x} - 1$
  - Inverse function: $f^{-1} = \frac{1}{x} - 1$
  - For the original function, the vertical asymptote was $x = -1$
  - For the inverse function, this becomes a horizontal asymptote of $y = -1$
- $y = (x + 1)^2$
  - This is a parabola
  - This is a function, but it is not a 1:1 function
- $y = x + 1$
  - $x = y + 1$
  - $y = x - 1$
- $y = (x + 1)^3$
  - $x = (y + 1)^3$
  - $\sqrt[3]{x} = y + 1$
  - $y = \sqrt[3]{x} - 1$
- $y = \sqrt{x + 1}$
  - $x = \sqrt{y + 1}$
  - $x^2 = y + 1$
  - $y = x^2 - 1$
- "given ... found ... claim ... $y = \frac{1}{x} - 1$ is inverse to $\frac{1}{x + 1} = y$
  - $f^{-1}(f(x))$
  - $y = \frac{1}{x + 1}$
- To prove that $y = \frac{1}{x} - 1$ is inverse to $\frac{1}{x + 1}$, show that either of these equations is true
  1. $f^{-1}(f(x)) = x$
  2. $f(f^{-1}(x)) = x$
- Then you would graph the inverse function as well
- Line of symmetry is always $y = x$
- Given $y = 3(x - 1)^3 - 2 = g(x)$
  - Find inverse
    - $x = 3(y - 1)^3 - 2$
    - $x + 2 = 3(y - 1)^3$
    - $\frac{x + 2}{3} = (y - 1)^3$
    - $y - 1 = \sqrt[3]{\frac{x + 2}{3}}$
    - $y = \sqrt[3]{\frac{x + 2}{3}} + 1$
    - $g^{-1}(x) = \sqrt[3]{\frac{x + 2}{3}} + 1$
  - Prove through function composition that the functions are an inverse of each other
  - Graph the function and the inverse function
- Major three steps
  - Find inverse by switching x and y, then solving for y
  - Prove through function composition that the functions are inverse
  - Graph the function and the inverse function (choosing the easier function to start graphing)
