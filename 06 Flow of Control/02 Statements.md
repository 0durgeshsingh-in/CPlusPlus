## Statements in C++

* A statement in C++ is a single instruction that the compiler executes when the program runs. 
* Every statement in C++ ends with a semicolon ( ; ).
* Statements determine the flow of execution in a program.

### Types of Statements in C++

**1. Expression Statements**

These statements perform an operation and end with a semicolon.

```cpp

Example:

int x = 10;  // Assignment statement
x = x + 5;   // Arithmetic expression statement
cout << x;   // Output statement

```


**2. Compound Statements (Block Statements)**

A group of statements enclosed within curly braces {}.

Used in loops, conditionals, and functions.

```cpp

Example:

{
    int a = 5;
    int b = 10;
    cout << a + b;
}  // This is a compound statement

```


3. Selection Statements (Decision-Making)

Used to make choices based on conditions.

Example:

if (age >= 18) {
    cout << "You can vote.";
} else {
    cout << "You cannot vote.";
}


4. Iteration Statements (Looping)

Used to repeat a block of code multiple times.

Example:

for (int i = 1; i <= 5; i++) {
    cout << i << " ";
}


5. Jump Statements

Used to alter the flow of execution.

Types:

break → Exits a loop.

continue → Skips the current iteration.

return → Exits a function.

goto → Jumps to a labeled statement.


Example:

for (int i = 1; i <= 5; i++) {
    if (i == 3) continue;
    cout << i << " ";
}


Conclusion

Statements are the building blocks of a C++ program. They define what the program does and how it behaves, including assigning values, making decisions, looping, and controlling execution flow.