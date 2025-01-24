increment (++) and decrement (--) operators are used to increase or decrease the value of a variable by 1. 
They can be used in both prefix and postfix forms, with slightly different behaviors.

# Increment Operator (++)
 - Prefix (++variable): Increases the value of the variable first, then returns the updated value.
 - Postfix (variable++): Returns the current value of the variable, then increases it.

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

```
