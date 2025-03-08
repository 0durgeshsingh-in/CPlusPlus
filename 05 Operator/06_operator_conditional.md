# Conditional Operator
- The conditional operator in C++ (also called the ternary operator) is a shorthand for an if-else statement.
- It allows you to evaluate a condition and choose between two expressions based on whether the condition is true or false.

```cpp
  condition ? expression1 : expression2;
```

  - **condition** : An expression that evaluates to true or false.
  - **expression1** : This is evaluated if the condition is true.
  - **expression2** : This is evaluated if the condition is false.

```cpp
  #include <iostream>
  using namespace std;

  int main() {
      int a = 10, b = 20;
  
      // Using conditional operator
      int max = (a > b) ? a : b;
  
      cout << "The larger number is: " << max << endl;
      return 0;
  }
```
