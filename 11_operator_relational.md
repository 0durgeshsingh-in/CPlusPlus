# Relational operators
Relational operators are used to compare two values and return a boolean result (true or false).
 1. (Equal to) == 
 2. (Not equal to) != 
 3. (Less than)   < 
 4. (Greater than)   >
 5. (Less than or equal to)  <= 
 6. (Greater than or equal to)   >=

```cpp
#include <iostream>
using namespace std;
int main() {
    int a = 5, b = 10;
    cout << (a == b) << endl;  // Output: 0 (false)
    cout << (a != b) << endl;  // Output: 1 (true)
    cout << (a < b) << endl;   // Output: 1 (true)
    cout << (a > b) << endl;   // Output: 0 (false)
    cout << (a <= b) << endl;  // Output: 1 (true)
    cout << (a >= b) << endl;  // Output: 0 (false)
    return 0;
}
```

- **Note** : Relational operators are commonly used in conditional statements like if, while, and for loops.
