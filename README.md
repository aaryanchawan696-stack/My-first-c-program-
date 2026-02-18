# My-first-c-program-
#include <iostream>
using namespace std;

int main() {
    int first_number, second_number, sum;
    
    // Asking for user input
    cout << "Enter two integers: ";
    cin >> first_number >> second_number;

    // Carrying out the addition
    sum = first_number + second_number;

    // Displaying the result
    cout << first_number << " + " << second_number << " = " << sum;

    return 0;
}
