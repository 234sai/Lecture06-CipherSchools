# Lecture06-CipherSchools



in this lecture i learned how to write a program a switch case and else if program and also i learned a sample program here is the sample program of combined 


#include <iostream>

int main() {
    int number;

    // Prompt the user for input
    std::cout << "Enter a number between 1 and 5: ";
    std::cin >> number;

    // Using if-else statements
    if (number == 1) {
        std::cout << "You entered one.\n";
    } else if (number == 2) {
        std::cout << "You entered two.\n";
    } else if (number == 3) {
        std::cout << "You entered three.\n";
    } else if (number == 4) {
        std::cout << "You entered four.\n";
    } else if (number == 5) {
        std::cout << "You entered five.\n";
    } else {
        std::cout << "Invalid number!\n";
    }

    // Using switch-case statements
    switch (number) {
        case 1:
            std::cout << "Switch: You entered one.\n";
            break;
        case 2:
            std::cout << "Switch: You entered two.\n";
            break;
        case 3:
            std::cout << "Switch: You entered three.\n";
            break;
        case 4:
            std::cout << "Switch: You entered four.\n";
            break;
        case 5:
            std::cout << "Switch: You entered five.\n";
            break;
        default:
            std::cout << "Switch: Invalid number!\n";
            break;
    }

    return 0;
}
