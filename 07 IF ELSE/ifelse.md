## if-else in C++

* The if-else statement is a fundamental control structure in C++ that allows the program to make decisions based on conditions.


---

# **1. Syntax of if Statement**

* The if statement checks whether a condition is true or false. If the condition evaluates to true, the block of code inside the if statement executes. If it is false, the program skips that block.

Syntax:
```cpp
if (condition) {
    // Code to execute if condition is true
}
```

Example:

```cpp
#include <iostream>

int main() {
    int x = 10;

    if (x > 0) {  // Condition is true
        std::cout << "x is positive." << std::endl;
    }

    return 0;
}

Output:

x is positive.

Here, since x is 10, and 10 > 0 is true, the message is displayed.

```

---

# **2. if-else Statement**

If the condition in the if statement is false, the else block executes.

Syntax:
```cpp
if (condition) {
    // Code to execute if condition is true
} else {
    // Code to execute if condition is false
}
```

Example:
```cpp

#include <iostream>

int main() {
    int num;
    std::cout << "Enter a number: ";
    std::cin >> num;

    if (num % 2 == 0) {
        std::cout << "The number is even." << std::endl;
    } else {
        std::cout << "The number is odd." << std::endl;
    }

    return 0;
}
```
Explanation:

If the number is divisible by 2 (num % 2 == 0), it prints "The number is even."

Otherwise, it prints "The number is odd."


Example Outputs:

Enter a number: 4
The number is even.

Enter a number: 7
The number is odd.


---

3. if-else if-else Statement

When there are multiple conditions to check, we use else if.

Syntax:

if (condition1) {
    // Executes if condition1 is true
} else if (condition2) {
    // Executes if condition2 is true
} else {
    // Executes if none of the above conditions are true
}

Example:

#include <iostream>

int main() {
    int num;
    std::cout << "Enter a number: ";
    std::cin >> num;

    if (num > 0) {
        std::cout << "The number is positive." << std::endl;
    } else if (num < 0) {
        std::cout << "The number is negative." << std::endl;
    } else {
        std::cout << "The number is zero." << std::endl;
    }

    return 0;
}

Explanation:

1. If num > 0, it prints "The number is positive."


2. If num < 0, it prints "The number is negative."


3. If num == 0, it prints "The number is zero."



Example Outputs:

Enter a number: 5
The number is positive.

Enter a number: -3
The number is negative.

Enter a number: 0
The number is zero.


---

4. Nested if-else Statement

An if-else statement inside another if-else is called nested if-else.

Example:

#include <iostream>

int main() {
    int num;
    std::cout << "Enter a number: ";
    std::cin >> num;

    if (num >= 0) {  // Outer if
        if (num == 0) {  // Inner if
            std::cout << "The number is zero." << std::endl;
        } else {
            std::cout << "The number is positive." << std::endl;
        }
    } else {
        std::cout << "The number is negative." << std::endl;
    }

    return 0;
}

Example Outputs:

Enter a number: 8
The number is positive.

Enter a number: 0
The number is zero.

Enter a number: -5
The number is negative.

Explanation:

1. If num >= 0, the program enters the outer if.


2. Inside the outer if, it checks if num == 0 and prints "The number is zero."


3. Otherwise, it prints "The number is positive."


4. If num < 0, the outer else executes, printing "The number is negative."




---

5. Using Logical Operators in if Conditions

You can combine multiple conditions using logical operators:

&& (AND) → Both conditions must be true.

|| (OR) → At least one condition must be true.

! (NOT) → Negates the condition.


Example with && (AND)

#include <iostream>

int main() {
    int age;
    std::cout << "Enter your age: ";
    std::cin >> age;

    if (age >= 18 && age <= 65) {
        std::cout << "You are eligible to work." << std::endl;
    } else {
        std::cout << "You are not eligible to work." << std::endl;
    }

    return 0;
}

Explanation:

If age is between 18 and 65 (inclusive), it prints "You are eligible to work."

Otherwise, it prints "You are not eligible to work."



---

6. Ternary Operator (Shorthand for if-else)

The ternary operator (? :) is a shorthand way to write simple if-else statements.

Syntax:

condition ? expression_if_true : expression_if_false;

Example:

#include <iostream>

int main() {
    int num;
    std::cout << "Enter a number: ";
    std::cin >> num;

    std::cout << (num % 2 == 0 ? "Even" : "Odd") << std::endl;

    return 0;
}

Explanation:

If num is even, it prints "Even".

Otherwise, it prints "Odd".



---

Summary Table


---

Would you like any additional examples or explanations?

