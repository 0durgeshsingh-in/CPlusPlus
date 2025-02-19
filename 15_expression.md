# Expression
- An expression is a combination of operands (such as variables, constants, or literals) and operators (such as +, -, *, /, etc.) that is evaluated to produce a single value.

### Types of Expression

##### 1. Constant Expression
- An expression consisting entirely of constants and evaluates at compile time.
```cpp
const int result = 10 + 20; // Compile-time evaluation
```
##### 2. Arithmetic  Expression
- An expression Involves arithmetic operators to perform mathematical operations.
```cpp
    int sum = a + b;       // Addition
    int product = a * b;   // Multiplication
```
##### 3. Relational (Comparison) Expression
- Evaluates to a boolean value (true or false) by comparing two operands using relational operators.
```cpp
   bool result = a > b; // true if a is greater than b
```
##### 4. Logical Expression
- Uses logical operators (&&, ||, !) to combine or negate boolean values.
```cpp
   bool result = (a > b) && (b < c); // Logical AND
```
##### 5. Bitwise Expression
- Performs bitwise operations on integer values using operators like &, |, ^, ~, <<, >>.
```cpp
  int result = a & b; // Bitwise AND
  int shifted = a << 2; // Left shift
```

##### 6. Assignment Expression
- Assigns a value to a variable using the assignment operator (=).
```cpp
    int a = 5; // Assignment
    a += 10;   // Compound assignment
```
##### 7. Conditional (Ternary) Expression
- Uses the ternary operator (? :) to evaluate and return a value based on a condition.
```cpp
    int max = (a > b) ? a : b; // If a > b, return a; else return b
```
##### 8. Function Call Expression
- Calls a function and uses its return value.
```cpp
    int result = std::max(10, 20); // Calls the max function
```

##### 9. Pointer and Address Expressions
- Expressions involving pointers and memory addresses using operators like *, &.
```cpp
    int x = 10;
    int* ptr = &x; // Address-of operator
    int y = *ptr;  // Dereference operator
```
##### 10. Combinational Expressions
- Combines multiple types of expressions in a single statement.
```cpp
    int result = (a + b) * (c > d ? c : d); // Arithmetic + Conditional + Relational
```



