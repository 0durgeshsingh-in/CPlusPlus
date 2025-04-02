In C++, if-else statements are used for decision-making. The syntax is:

#include <iostream>

int main() {
    int number;
    std::cout << "Enter a number: ";
    std::cin >> number;

    if (number > 0) {
        std::cout << "The number is positive.\n";
    } else if (number < 0) {
        std::cout << "The number is negative.\n";
    } else {
        std::cout << "The number is zero.\n";
    }

    return 0;
}

Explanation:

1. The if condition checks if number > 0. If true, it executes the first block.


2. The else if condition checks if number < 0. If true, it executes the second block.


3. If neither condition is met, the else block executes.



Would you like more examples, such as nested or multiple if-else statements?

