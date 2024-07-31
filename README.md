# Pythagoras
advanced calculator in python

# features
- Basic arithmatics
- the ability to define functions that would be stored in memory
- plot functions
- trigonometry
- calculus (integration and differentiation)

  # usage

  you can use it as a basic calculator
  
    `5+5` adition
  
    `5/5` devision
  
    `5-5` subtraction
  
    `5*5` multiplication
  
    `5**5` powers (note: for roots, use a fractional power, eg 25**0.5 = 5)

  trigonometry
  
    `sin(x)` (where X can be any value)

    currently supported trigonometric functions are `sin`, `cos`, `tan`, `arcsin`, `arccos`, and `arctan` (for `arc*` functions, use `a*` (for example `asin()`)

  store a function

    `F = 32*sin(x)` (note that a function is always going to take x as an argument)

    `F(3)` will output the value of `32*sin(3)`

    note: a function's letter is always uppercase, lowercase letters are reserved for variables

  plot a function

    `plot F`

  calculus

  int for integration, diff for differentiation, they can take either a function or an expression

    `diff sin(x)`

    `diff F`

    `int sin(x)`

    `int F`

  note: at the moment, you can't request the value of an integral or a derivative fron the `int`/`diff` functions directly, so you'd have to copy the result and store in in a function, and then request it's value

  # dependancies

  - matplotlib
  - numpy
  - sympy

  # installation

  it's a simple python script, there is nothing to install, just use pip (or your package manager) to install the required libraries, and copy the python script to somewhere in your path, after that you could run it by running the command `Pythagoras`
    
