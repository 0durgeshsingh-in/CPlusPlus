# Derived Data Types
  In C++, derived data types are types that are created using built-in or existing data types. These types provide additional functionality, structure, or abstraction.
  1. Arrays
  2. Pointers
  3. References
  4. Functions

**Array**
   - Arrays are collections of elements of the same data type stored in contiguous memory locations.
  - Syntax: dataType arrayName[size];
  - Example:
```cpp
   int numbers[5] = {1, 2, 3, 4, 5};
```

**Pointers**
   - Pointers are variables that store the memory address of another variable.
   - Syntax: dataType* pointerName;
  - Example:
```cpp
   int a = 10;
   int* p = &a;
```
**References**
   - References are aliases for existing variables.
   - Syntax: dataType& referenceName = variableName;
  - Example:
```cpp
    int x = 5;
    int& ref = x;
```

**Functions**
   - Functions are blocks of code that perform specific tasks and can be treated as derived types because they are declared and defined based on fundamental types.
```cpp
    int add(int a, int b) {
    return a + b;
    }
```

 --- 
## User Defined Derived DataTypes
  1. Classes and Objects
  2. Structures
  3. Enumerations

**Classes and Objects**
   - Classes are user-defined types that represent a combination of variables and functions (data and methods).
```cpp
    class Car {
public:
    string brand;
    int speed;
};
```  

**Structures**
   - Structures are user-defined data types used to group different data types under one name.
```cpp
    struct Point {
    int x;
    int y;
};
```  

**Enumerations**
   - Enumerations are user-defined types that assign names to integral constants.
```cpp
   enum Color { RED, GREEN, BLUE };
``` 

