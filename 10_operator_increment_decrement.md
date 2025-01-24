increment (++) and decrement (--) operators are used to increase or decrease the value of a variable by 1. 
They can be used in both prefix and postfix forms, with slightly different behaviors.

# Increment Operator (++)
 - **Prefix (++variable)**  : Increases the value of the variable first, then returns the updated value.
 - **Postfix (variable++)** : Returns the current value of the variable, then increases it.
```cpp
   #include <iostream>
   using namespace std
    int main() {
        int a = 5; 
        // Prefix increment
        cout << "Prefix Increment: " << ++a << endl; // Outputs 6 (a is now 6)
        // Postfix increment
        cout << "Postfix Increment: " << a++ << endl; // Outputs 6 (a becomes 7 after this line)
        cout << "Final Value of a: " << a << endl; // Outputs 7
        return 0;
    }
````

# Decrement Operator (--)
  - **Prefix (--variable)**  : Decreases the value of the variable first, then returns the updated value.
  - **Postfix (variable--)** : Returns the current value of the variable, then decreases it.

```cpp
    #include <iostream>
    using namespace std;  
    int main() {
        int b = 10;
        // Prefix decrement
        cout << "Prefix Decrement: " << --b << endl; // Outputs 9 (b is now 9)
        // Postfix decrement
        cout << "Postfix Decrement: " << b-- << endl; // Outputs 9 (b becomes 8 after this line)
        cout << "Final Value of b: " << b << endl; // Outputs 8
        return 0;
    }
```

##### Key Differences Between Prefix and Postfix
 1. **Prefix (++variable or --variable):**
    - The operation is performed before the variable is used.
    - Typically slightly faster since it doesn’t involve storing a temporary copy of the original value.

2. **Postfix (variable++ or variable--):**
   - The operation is performed after the variable is used.
   - Requires storing a temporary copy of the variable’s original value, which can be slightly less efficient.
    

