# Basic Syntax
## Variable Declaration
`let x: type = value;`

Variable declarations are the same as Rust. All variables are immutable by default. 

`let mut x: type = value`

Use the mut variables to declare a mutable variable.

`let x = value;`

The type does not need to be specified as there'll be type inference.
## Operators
### Arithmetic  Operators
`5 + 2` (evaluates to 7)
The addition operator (+) adds two values together, returns a signed integer (or a float depending on the values being added).
`5 - 2` (evaluates to 3)
The subtraction operator (-) subtracts the left value from the right value, returns a signed integer (or float depending on the types of the values).
`5 / 2` (evaluates to 2.5)
A single division operator (/) divides the value to the left of the operator by the value to the right of the operator, and returns a floating point number.
`5 // 2` (evaluates to 2)
Double division operators (//) divide the value to the left by the value to the right, returns only the integer part.
`5 % 2` (evaluates to 1)
The modulo operator (%) returns the remainder performed after the value to the left of the operator gets divided by the value on the right.
### Relational Operators
`5 == 2` (Evaluates to False, or 0) 
Checks if two operands share the same value.
`5 >= 2` (Evaluates to True, or 1)
Checks if the operand to the left is greater or equal to the operand on the right.
`5 <= 2` (Evaluates to False, or 0)
Checks if the left operand is lesser than or equal to the left operand.
`5 != 2` (Evaluates to True, or 1
Checks if the two operands are not equal.
`5 > 2` (Evaluates to True, or 1
Checks if the left operand is greater than the right operand.
`5 < 2` (Evaluates to False, or 0)
Checks if the left operand is less than the right operand.
### Logical Operators
`True && False` (Evalutes False, or 0)
`False && True` (Evalutes False, or 0)
`False && False` (Evalutes False, or 0)
`True and True` (Evaluates to True, or 1)
Evaluates the logical and operation between two boolean statements or values.
`True || False` (Evaluates to True, or 1)
`False || True` (Evaluates to True, or 1)
`False || False` (Evalutes False, or 0)
`True || True` (Evaluates to True, or 1)
Evaluates the logical or operation between two logical statements or boolean values.
`True |\ False` (Evaluates to True, or 1)
`False |\ True` (Evaluates to True, or 1)
`False |\ False` (Evalutes False, or 0)
`True |\ True` (Evalutes False, or 0)
Evaluates whether the truth value of both operands are the same; if they are, it evaluates to false; if they aren't, it evaluates to true.
`!True` (Evaluates to False, or 0)
`!False` (Evaluates to True, or 1)
`!(True && False)` (Evaluates to True, or 1)
Reverses the logical state of its operand. Can work in tandem with other operators.
### Bitwise Operators
`let x: i8 = 60` (in binary 60 is 0011 1100)
`let y: i8 = 13`(in binary 13 is 0000 1101)
`let A: i8 = x & y` (this is  0011 1100 & 0000 1101 which evaluates to 0000 1100 or 12)
The bitwise And operator (&) does an And operation on the digits in the same place of each binary digit of the number to the left by   the number to the right.
`let  B = x | y` (this is 0011 1100 | 0000 1101 which evaluates to 0011 1101 or 61)
The bitwise Or operator does a bitwise Or operation on the digits in the same place of each binary digit of the number to the left by the number to the right.
