# Logical operators
- Logical operators in C++ are used to perform logical operations on boolean expressions, resulting in a true or false value.

  1. **AND (&&)**: Checks if both conditions are true.
     - (a > 0 && b > 0) → true && false → false.
  2. **OR (||)**: Checks if at least one condition is true.
     - (a > 0 || b > 0) → true || false → true.
  3. **NOT (!)**: Negates the result of a condition.
     - !(a > 0) → !true → false.

  ```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 5, b = -3;
    // Logical AND
    cout << (a > 0 && b > 0) << endl;  // Output: 0 (false)
    // Logical OR
    cout << (a > 0 || b > 0) << endl;  // Output: 1 (true)
    // Logical NOT
    cout << !(a > 0) << endl;          // Output: 0 (false)
    return 0;
}
```
