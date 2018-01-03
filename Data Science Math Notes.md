# Data Science Math NOTES

## Functions

**Function**: A rule for a relationship between an input, or independent, quantity and an output, or dependent, quantity in which **each input value uniquely determines one output value**. We say “the output is a function of the input.”

**Vertical Line Test**
The vertical line test is a handy way to think about whether a graph defines the vertical output as a function of the horizontal input. Imagine drawing vertical lines through the graph. If any vertical line would cross the graph more than once, then the graph does not define only one vertical output for each horizontal input.

#### Inequality                       

- 5 < h <= 10
- 5 <= h < 10
- 5 < h < 10
- h < 10
- h >= 10
- all real numbers

#### Interval notation

- (5, 10]
- [5, 10)
- (5, 10)
- (-∞,10)
- [10, ∞)
- (∞, ∞)

### Toolkit Functions

![Graphs of basic functions that you should know on sight.](https://github.com/betsyrosalen/datascienceNOTES/blob/master/Graphs%20of%20the%20Toolkit%20Functions.PNG "Toolkit Functions")

![Graphs of basic functions that you should know on sight.](https://math.libretexts.org/@api/deki/files/925/CNX_Precalc_Figure_01_03_012.jpg?revision=1)

### Composition of Functions
When the output of one function is used as the input of another, we call the entire operation a composition of functions. We write f(g(x)), and read this as “f of g of x” or “f composed with g at x”.
An alternate notation for composition uses the composition operator: o

(f o g)(x) is read “f of g of x” or “f composed with g at x”, just like f(g(x)).

### Vertical Shift
Given a function f(x), if we define a new function g(x) as g(x) = **f(x)+k**, where k is a constant
then g(x) is a vertical shift of the function f(x), where all the output values have been increased by k.

- If **k is positive**, then the graph will **shift up**
- If **k is negative**, then the graph will **shift down**

### Horizontal Shift
Given a function f(x), if we define a new function g(x) as g(x) = **f(x+k)**, where k is a constant
then g(x) is a horizontal shift of the function f(x)

- If **k is positive**, then the graph will **shift left**
- If **k is negative**, then the graph will **shift right**

### Reflections
Given a function f(x), if we define a new function g(x) as g(x) = **-f(x)**,
then g(x) is a **vertical reflection** of the function f(x), sometimes called a reflection about the x-axis

If we define a new function g(x) as **f(-x)**,
then g(x) is a **horizontal reflection** of the function f(x), sometimes called a reflection about the y-axis

### Vertical Stretch/Compression
Given a function f(x), if we define a new function g(x) as g(x) = **kf(x)**, where k is a constant
then g(x) is a **vertical stretch or compression** of the function f(x).

- If k > 1, then the graph will be stretched
- If 0 < k < 1, then the graph will be compressed
- If k < 0, then there will be combination of a vertical stretch or compression with a vertical reflection

### Combining Transformations
When combining vertical transformations, it is very important to consider the order of the transformations. For example, vertically shifting by 3 and then vertically stretching by 2 does not create the same graph as vertically stretching by 2 and then vertically shifting by 3. The order follows nicely from order of operations.

#### Combining Vertical Transformations
When combining vertical transformations written in the form af(x) + k,
first vertically stretch by a, then vertically shift by k.

## Linear Functions

#### Slope and Increasing/Decreasing

m = change in y over the change in x = (y2 - y1) / (x2 - x1)

#### Point-Slope Equation of a Line

Point-slope is a specific form of linear equations in two variables:
y - b = m(x - a) 

When an equation is written in this form, m gives the slope of the line and (a,b) is a point the line passes through.

#### Graphical Interpretation of a Linear Equation

#### Finding **Horizontal Intercept**

## Exponents

### Laws of Exponents:
2. x^a / x^b = x^(a-b)  
3. (x^a)^b = x^ab  
4. (xy)^a = x^a⋅y^a  
5. (x/y)^b = x^b / y^b  
6. x^0 = 1, provided x != 0  
7. x^-n = 1/x^n, provided x != 0    
8. x^1/n = the nth root of x, provided x != 0  

## Quadratics

### Forms of Quadratic Functions

The **transformation form** of a quadratic function is **f(x) = a(x−h)^2 + k**
 
The **vertex** *(the lowest point or turnaround point of the graphed curve)* of the quadratic function is located at (h, k), where h and k are the numbers in the transformation form of the function. Because the vertex appears in the transformation form, it is often called the **vertex form**.

#### Intercepts

We can find the **horizontal intercepts** by solving for when the output will be zero. Depending upon the location of the graph, we might have zero, one, or two horizontal intercepts.

#### Quadratic Formula


![Quadratic Formula.](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/Quadratic_formula.svg/200px-Quadratic_formula.svg.png)

## Polynomials and Rational Functions 

### Polynomial Functions







#### Intercepts

Find **vertical intercepts** by solving for f(0)

Finding **horizontal intercepts** can be challenging, so technology is often used.

### Rational Functions

#### Vertical and Horizontal Asymptotes

The vertical asymptotes of a rational function will occur where the denominator of the function is equal to zero and the numerator is not zero.


The horizontal asymptote of a rational function can be determined by looking at the degrees of the numerator and denominator.
- Degree of denominator < degree of numerator: No horizontal asymptote

#### Intercepts
As with all functions, a rational function will have a **vertical intercept when the input is zero**, if the function is defined at zero. It is possible for a rational function to not have a vertical intercept if the function is undefined at zero.


## Exponential Functions

Where:


### Euler’s Number: e ≈ 2.718282
See textbook page 62 for explanation

### Graphical Features of Exponential Functions


The range of the function is (0,∞)

When sketching the graph of an exponential function, it can be helpful to remember that the graph will pass through the points (0, a) and (1, ab).


- If b > 1, as x → ∞, f(x) → ∞ and as x → −∞ , f(x) → 0
- If 0 < b < 1, as x→∞, f(x) → 0 and as x → −∞, f(x) → ∞

## Logarithmic Functions

### Common and Natural Logarithms

The natural log is the logarithm with base e, and is typically written ln(x) .