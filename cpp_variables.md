# C++ Variables
- In C++, variables are named storage locations in memory that are used to store data. 
- A variable has a type, which defines the kind of data it can hold, and a name, which is used to refer to the variable in the program.
- Variables are fundamental building blocks in programming, as they allow you to manipulate and store data dynamically during the execution of a program.

#### Characteristics of Variables in C++
- **1.Type:** Determines the kind of data the variable can hold (e.g., integers, floating-point numbers, characters, etc.).
-  **2.Name:** The identifier used to access the variable.
-  **3.Scope:** Defines the part of the program where the variable can be accessed.
-  **4.Scope:** Determines how long the variable exists in memory.
  
####  Declaring Variables
To declare a variable in C++, you specify its type followed by its name:
```cpp
int age; // Declaration of an integer variable named 'age'
```
####  Initialize Variables
You can also initialize a variable at the time of declaration:
```cpp
int age = 25; // Declaration and initialization
```
## Rules for Naming Variables
- Must begin with a letter or underscore (_).
- Can consist of letters, digits, and underscores.
- Cannot use reserved keywords (e.g., int, return).
- Case-sensitive (e.g., age and Age are different).

## Dynamic Initialization  
C++ refers to the process of initializing variables at runtime, rather than at compile-time. This allows the initialization of a variable to depend on calculations or user input that occur during program execution.

````cpp
#include <iostream>
using namespace std;

int main() {
    int a = 5, b = 10;
    int sum = a + b; // Dynamically initialized using an expression
    cout << "Sum: " << sum << endl;
    return 0;
}
````


 
