## 3.4: Composition of Functions
### Combining Functions Using Algebraic Operations
- Function composition is one way to combine existing functions. We can also sum two functions, take the difference, product, ratio, etc. for any pair of functions that have the same kinds of inputs and the same kinds of outputs

### Create a Function by Composition of Functions
- Performing algebraic operations on functions combines them into a new function, but you can also create functions by composing functions
- The process of combining functions that the output of one function becomes the input of another is known as a composition of functions, with the resulting function known as a **composite function**
  - With two functions, $f(x)$ and $g(x)$, they can be combined into a composite function $f(g(x))$ or $g(f(x))$
- The order of operations when evaluating composite functions is to start with the innermost parentheses first, the work towards the outside
  - Note that the range of the inside function needs to be in the domain of the outside function
##### Composition of Functions
- When the output of one function is used as the input of another, we call the entire operation a composition of functions. For any input $x$ and functions $f$ and $g$, this action defines a **composite function**, which we write as $f \circ g$ such that
  - $(f \circ g)(x) = f(g(x))$
- The domain of the composite function $f \circ g$ is all $x$ such that $x$ is in the domain of $g$ and $g(x)$ is in the domain of $f$.
- It is important to realize that the product of functions $fg$ is not the same as the function composition $f(g(x))$, because, in general, $f(x)g(x) \ne f(g(x))$.

### Evaluating Composite Functions
- Once we compose a new function from two existing functions, we need to be able to evaluate it for any input in its domain, evaluating the inner function using the starting input and then use the inner function's output as the input for the outer function.
#### Evaluating Composite Functions Using Tables
- When working with functions given as tables, read input and output values from the table entries and work inside to outside
#### Evaluating Composite Functions Using Graphs
- When given individual functions as graphs, the process to evaluate composite functions is similar to tables. Read the input and output values, but from the x- and y-axes of the graphs
##### How To
- Given a composite function and graphs of its individual functions, evaluate it using the information provided by the graphs
  1. Locate the given input to the inner function on the x-axis of its graph
  2. Read off the output of the inner function from the y-axis of its graph
  3. Locate the inner function output on the x-axis of the graph of the outer function
  4. Read the output of the outer function from the y-axis of its graph. This is the output of the composite function
#### Evaluating Composite Functions Using Formulas
- When we have formulas, the process of working inside-out remains the same, with the output of the inner function being passed as the input to the outer function
##### How To
- Given a formula for a composite function, evaluate the function
  1. Evaluate the inside function using the input value or variable provided
  2. Use the resulting output as the input to the outside function

### Finding the Domain of a Composite Function
- The domain of a composite function is dependent on the domains of each of the functions that make up the composite function.
- The domain of the composite function $f \circ g$ consists of only those inputs in the domain of $g$ that produce outputs from $g$ belonging to the domain of $f$
##### Domain of a Composite Function
- The domain of a composite function $f(g(x))$ is the set of inputs $x$ in the domain for $g$ for which $g(x)$ is in the domain of $f$
##### How To
- Given a function composition $f(g(x))$, determine its domain
  1. Find the domain of $g$
  2. Find the domain of $f$
  3. Find those inputs $x$ in the domain of $g$ for which $g(x)$ is in the domain of $f$. That is, exclude those inputs $x$ from the domain of $g$ for which $g(x)$ is not in the domain of $f$. The resulting set is the domain of $f \circ g$

### Decomposing a Composite Function into is Component Functions
- Somtimes we need to decompose a complicated function, or write is as a composition of simpler functions.
- For example a function $f(x) = \sqrt{5 - x^2}$ can be decomposed as $h(x) = 5 - x^2$ and $g(x) = \sqrt{x}$

---
In-class notes
### Functions and composition of Functions
- $f(x) = x^4 - x^2 - 2$
- It is a function because there are two "letters" involved, $y$ and $x$
- If you had $x^4 - x^2 -2 = 0$, this **is not** a function, it is just an equation
  - This is "find the values of x where y is equal to zero"
- A function, for every chosen x, you will have one unique y
- When you have a function, you don't have a single "solution", but rather an infinite number of ordered pairs (x, y)
  - x is your independent variable, y is your dependent variable
- You could substitute single values of x (with a t-table) into your function to find values of y, but this is inefficient
- For every function or graph, we are interested in the most important points
  - x-intercept: (y = 0)
  - y-intercept(s): (x = 0)
  - end behavior: x -> $\infty$ or x -> $-\infty$
  - min/max (if possible to know) - this is also called the vertex
    - This is a calculus task, unless we are using quadratic functions and we can easily find the vertex
  - When you find the x-intercept, you are finding where y = 0
  - When you find the y-intercept, you are finding where x = 0
- Anything that crosses the y-axis more than once is not a function, but rather a "relation"
- $y = x^3 - x^2 - 4x + 4$
  - This is a function, because it is not set equal to a specific value for y
  - Let x = 0, this will be your y-intercept
  - To find the x-intercept, with four terms, you can factor by grouping
  - $x^2(x - 1) - 4(x - 1) = 0$
  - $(x - 1)(x + 2)(x - 2) = 0$
    - $x = 1; x = -2, x = 2$
  - The interesting points are
    - $(-2, 0)$
    - $(0, 4)$
    - $(1, 0)$
    - $(2, 0)$
- If you have $y = ax^{n}$ and n is even
  - $a$ is positive The tails of the graph will both go up
  - $a$ is negative, the tails of the graph will both go down
- If you have $y = ax^n$ and $n$ is odd
  - The branches will go in opposite directions
  - If $a$ is greater than zero, the left side will be down, right side will be up
  - If $a$ is less than zero, the left side will be up, right side will be down
- In graphing polynomial functions, your leading coefficient and the degree of the highest exponent determine the appearance of your function
### Composition of Functions
- "Composition of functions" is when you apply a function on the output of another function
- $y = f(x) = 3x - 5$
- $h(x) = 2 - \frac{1}{2}x$
- $g(x) = x^2$
- You can "chain" multiple functions together to put the output of a function into the input of another
- $g(h(f(x)))$
  - $f(3) = 4$
  - $h(4) = 0$
  - $g(0) = 0$
  - $g(h(f(3))) = 0$
  - Start reading from innermost function and go outward
- $g(f(h(0)))$
  - $h(0) = 2$
  - $f(2) = 1$
  - $g(1) = 1$
- $g(f(h(-2)))$
  - $h(-2) = 3$
  - $f(3) = 4$
  - $g(4) = 16$
- $f(h(g(2)))$
  - $g(2) = 4$
  - $h(4) = 0$
  - $f(0) = -5$
- $f(h(g(-3)))$
  - $g(-3) = 9$
  - $h(9) = -2.5$
  - $f(-2.5) = -12.5$
- $f(g(x))$
  - You can replace the function with its definition
  - $f(x^2) = 3x^2 - 5$
- $g(f(x))$
  - $g(3x - 5) = (3x - 5)^2$
- $f(f(x))$
  - $f(3x - 5) = 3(3x - 5) - 5$
- $h(g(x))$
  - $h(x^2) = 2 - \frac{1}{2}x^2$
- $f(h(x))$
  - $f(2 - \frac{1}{2}x) = 3(2 - \frac{1}{2}x) - 5$