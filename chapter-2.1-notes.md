## 2.1: The Rectangular Coordinate Systems and Graphs

---
In-class notes
#### Linear Functions
- Function means there is a relationship between x and y (x, y)
- x is our input, y is our output
- Not all x and y are called "functions"
- x is the independent variable and is your "run" (horizontal axis)
- y is the dependent variable and is your "rise" (vertical axis)
- Any set of (x, y) gives you a relation, but not all of them give you a function
- A function should have one and only one output for x
  - "For any given x, there should only be one y"
- For "linear" functions, the only thing you can do with it is add, subtract, divide, multiply
- These can be written in three forms
  - $y = mx + b$: "slope-y-intercept"
    - $m$ = slope: change in y over change in x, sometimes also referred to as "rise over run" = $\frac{y_2 - y_1}{x_2 - x_1}$ = $\frac{y_1 - y_2}{x_1 - x_2}$
    - $b$ = y-intercept, (0, $b$), $b$ is a number where you intersect the y-axis
    - Example: $y = -\frac{2}{3}x + 1$
      - $b = 1$, $y = (0, 1)$, $m = \frac{-2}{3}$
  - $y - y_1 = m(x - x_1)$: "slope-point"
    - $m = \frac{rise}{run}$, $(x_1, y_1)$ -> starting point, point on the line
    - Example: $y - 3 = 5(x + 2)$
      - In this example, you can pull $y_1 = 3$ and $x_1 = -2$
      - To find the y intercept, isolate $y = 5x + 13$
  - $ax + by = c$: "standard form"
    - This does not give you the x-intercept or y-intercept
    - When you see x and y on the same side and some other number on the other side, use the "tic tac toe" method.
      - In the equation, replace x with 0 to get y, $3(0) + 2y = 6$, y = 3
      - In the equation, replace y with 0 to get x, $3x + 2(0) = 6$, x = 2
    - Example: $3x + 2y = 6$
      - a = 3, b = 2, c = 6
    - Need to be able to calculate the slope, "rise over run", so in this instance -3/2
      - Need to remember that if we are sloping downward, the slope is negative
    - To find the slope without graphing, isolate and solve for y
      - $3x + 2y = 6$
      - $2y = -3x + 6$
      - $y = \frac{-3}{2}x + 3$
#### Distance formula
- If you have point $A(x1, y1)$ and point $B(x2, y2)$
  - $d(AB) = \sqrt{(x_1 - x_2)^2 + (y_1 - y_2)^2}$
  - Similar to the Pythagorean theorem, $a^2 + b^2 = c^2$, c is the hypotenuse
    - $a = y_1 - y_2$
    - $b = x_1 - x_2$
    - $c = \sqrt{(x_1 - x_2)^2 + (y_1 - y_2)^2}$
  - It does not matter if you subtract $x_1$ from $x_2$ or the other way around, because you are squaring the differences
- If you have point $A(x1, y1)$ and point $B(x2, y2)$ and want to find the midpoint
  - You can use $(x_1 + x_2) / 2$ and $(y_1 + y_2) / 2$, these will be your x and y coordinates of the midpoint
- Example, A = (-2, 7) and B = (3, -10)
  - distance = $\sqrt{(-2 - 3)^2 + (7 - (-10))^2} = \sqrt{314}$
  - $x = (-2 + 3) / 2 = \frac{1}{2}$
  - $y = (7 + -10) / 2 = \frac{-3}{2}$
  - midpoint = ($\frac{1}{2}, \frac{-3}{2}$)
- Example: $y = \frac{-3x + 5}{7} = \frac{-3}{7}x + \frac{5}{7}$
  - $m = \frac{-3}{7}$
  - $b = \frac{5}{7}$
```mermaid
graph TD
    A((y = 2x + 3)) --> B((Point 1: (0, 3)))
    A --> C((Point 2: (2, 7)))
```
#### Parallel and Perpendicular Lines
- Two lines are parallel when they **NEVER** intersect each other. These are lines that have the exact same slope, but can have different y-intercepts. If the y-intercept is the same, we can say they are the same line
- Perpendicular lines are those that meet at a 90-degree angle and have slopes that are negative reciprocals. For example, for the line $y = \frac{5}{2}$ then the perpendicular line would be $y = -\frac{2}{5}$
  - $m = \frac{a}{b}$ then the perpendicular line has a slope of $m = -\frac{b}{a}$

#### Examples
- $3x - 5 = 7$
  - $3x = 7 + 5$
  - $x = \frac{12}{3}$
  - $x = 4$
- $x - 5 = \frac{3}{7}$
  - $x = 5 + \frac{3}{7}$
  - $x = 5\frac{3}{7}$
- $5 - x = \frac{2}{3}$
  - $-x = \frac{2}{3} - 5$
  - $x = -\frac{2}{3} + 5$
  - $x = 4\frac{1}{3}$
- $7x + 2 = 3x - 9$
  - $7x - 3x + 2 = -9$
  - $4x = -9 - 2$
  - $4x = -11$
  - $x = \frac{-11}{4}$
- $3(x + 2) - 12 = 5(x + 1)$
  - $3x + 6 - 12 = 5x + 5$
- $12 - 5(x + 3) = 2x - 5$
  - $12 - 5x -15 = 2x - 5$
  - $12 -5x - 15 = 2x - 5$
  - $-3 - 5x = 2x - 5$
  - $-7x = -2$
  - $x = \frac{2}{7}$
- $\frac{1}{2} - \frac{1}{3} = \frac{4}{3}$
  - In this instance, start by finding the lowest common denominator (6)
  - $3 - 2x = 8$
- $\frac{1}{2}x + \frac{1}{3}(x + 2) - 4x = \frac{1}{5}(x - 3) - 2$
  - Lowest common denominator: 30
    - When the numbers are prime, just multiply them all together, so $2 \cdot 3 \cdot 5 = 30$
  - $15x + 10(x + 2) - 120x = 6(x - 3) - 60$
  - $15x + 10x + 20 - 120x = 6x - 18 - 60$
  - $-95x + 20 = 6x - 78$
  - $-101x = -98$
  - $x = \frac{98}{101}$
- $\frac{5}{x + 1} + \frac{1}{x - 3} = \frac{-6}{x^2-2x-3}$
  - Need to multiply by the common denominator, but need to factor first
  - When you have an equation, you want to get rid of the denominators
