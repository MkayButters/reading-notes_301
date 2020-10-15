## Functional Programming

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

- A _pure_ function definitions;
    1. It returns the same result if given the same arguments (it is also referred as deterministic)

        - If our function reads external files, it’s not a pure function
        - Any function that relies on a random number generator cannot be pure.
       
    2. It does not cause any observable side effects

        - Examples of observable side effects include modifying a global object or a parameter passed by reference.
        - Mutability is discouraged in functional programming.

#### Function programming benifits;

1. Easier to test.

2. Immutable, its state cannot change after it’s created.

- Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
    - ie. pure functions + immutable data = referential transparency

### Functions as First Class entities.

- Functions as first-class entities can:
    1. Refer to it from constants and variables
    2. Pass it as a parameter to other functions
    3. Return it as result from other functions


### Higher order functions.

1. Takes one or more functions as arguments,
 
    - or

2. Returns a function as its result


## Refactoring
- Refactoring is making your code smaller in easier to read sections without modifying what it actually does


[<===BACK](README.MD)