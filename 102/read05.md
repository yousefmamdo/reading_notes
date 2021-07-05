# summry  

## Expressions and operators
1. Expressions  
An expression is any valid unit of code that resolves to a value.Every syntactically valid expression resolves to some value butconceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.
2. Operators  
avaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:For example, 3+4 or x*y, x++ or ++x.

## Loops
+ Loops offer a quick and easy way to do something repeatedly. You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop.
For example:  
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
