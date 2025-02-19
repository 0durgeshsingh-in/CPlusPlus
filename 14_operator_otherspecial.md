## 1. Comma Operator
   - The comma operator in C++ is a unique operator that allows multiple expressions to be evaluated sequentially. It is represented by a comma ,.

```cpp
expression1, expression2;
```
- **expression1** is evaluated first (side effects are performed, if any).
- **expression2** is evaluated second, and its value becomes the result of the whole expression.

**Basic Usage:**
```cpp
    int a = 1, b = 2;
    int result = (a++, b++); // a++ is evaluated first, then b++.
    // Result is the value of b++, which is 2 before the increment.
```
**Usage in Loops:**
```cpp
   for (int i = 0, j = 10; i < j; i++, j--) {
    std::cout << "i: " << i << ", j: " << j << '\n';
   }
```
**Combining Statements:**
```cpp
    int x = 5, y = 10;
    int result = (x += 2, y -= 3); // x is incremented, y is decremented.
    // Result is the value of the second expression: y - 3 = 7.
    std::cout << "x: " << x << ", y: " << y << ", result: " << result << '\n';
```
----

