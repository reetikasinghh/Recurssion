# Recurssion
1) Aim:
The aim of this code is to calculate the factorial of a non-negative integer using a recursive function.

Theory:

Factorial of a non-negative integer 'n' (denoted as 'n!') is the product of all positive integers from 1 to 'n'. It is defined as:

scss
Copy code
n! = n × (n-1) × (n-2) × ... × 3 × 2 × 1
Recursive Approach:
The code uses a recursive function factorial(n) to calculate the factorial of 'n':

If 'n' is 0 or 1, the factorial is defined as 1.
For any other positive integer 'n', the factorial is calculated as n * factorial(n - 1). This recursive calculation continues until 'n' reaches 0 or 1, at which point the base case returns 1.
Algorithm:

Define a recursive function factorial(n) that takes an integer 'n' as an argument.

If 'n' is 0 or 1, return 1.
Otherwise, return n * factorial(n - 1).
In the main() function:

Declare an integer variable num to store the user's input.
Prompt the user to enter a non-negative integer and store it in num.
Check if the input is non-negative:
If 'num' is negative, display an error message indicating that factorial is not defined for negative numbers.
If 'num' is non-negative, call the factorial() function with 'num' as an argument to calculate the factorial.
Display the result as "Factorial of 'num' is 'result'".
Return 0 to indicate successful program execution.

Conclusion:
This code successfully calculates the factorial of a non-negative integer using a recursive function. It handles negative input cases by displaying an error message. The code demonstrates the recursive nature of factorial calculation and provides the factorial result for the user's input.


output :

![image](https://github.com/reetikasinghh/Recurssion/assets/139485681/23194620-75c0-45a0-b616-198dcb17e277)


2)Aim:
The aim of this code is to calculate the sum of integers from 1 to 'n' using recursion.

Theory:

The sum of integers from 1 to 'n' can be calculated using the following formula:

bash
Copy code
sum = 1 + 2 + 3 + ... + n
Recursive Approach:
The code uses a recursive function sumOfIntegers(n) to calculate the sum:

Base case: If 'n' is 1, the function returns 1 because the sum of integers from 1 to 1 is 1.
Recursive case: For any positive integer 'n' greater than 1, the function calculates the sum as n + sumOfIntegers(n - 1). This recursive calculation continues until 'n' reaches 1.
Algorithm:

Define a recursive function sumOfIntegers(n) that takes an integer 'n' as an argument.

Base case: If 'n' is 1, return 1.
Recursive case: Return n + sumOfIntegers(n - 1).
In the main() function:

Declare an integer variable n to store the user's input.
Prompt the user to enter a positive integer 'n' and store it in n.
Check if the input is valid (positive):
If 'n' is not positive, display an error message and exit with an error code.
If 'n' is positive, call the sumOfIntegers() function with 'n' as an argument to calculate the sum.
Display the result as "The sum of integers from 1 to 'n' is: 'result'".
Return 0 to indicate successful program execution.

Conclusion:
This code successfully calculates the sum of integers from 1 to 'n' using recursion. It handles non-positive input cases by displaying an error message and exiting with an error code. The code demonstrates the recursive nature of sum calculation and provides the sum result for the user's input.

output :
![image](https://github.com/reetikasinghh/Recurssion/assets/139485681/d9248616-424e-4b2a-8e6f-8974b4a65ea6)


3)Aim:
The aim of this code is to print a string in reverse using a recursive function.

Theory:

To print a string in reverse, you can use a recursive approach. The idea is to divide the problem into smaller subproblems, where each subproblem involves printing the last character of the string and then recursively printing the remaining substring without the last character.

Recursive Approach:

Base Case: If the string is empty (length is 0), return.
Print the last character of the string.
Call the recursive function with the substring excluding the last character.
Algorithm:

Include the necessary header files, including <iostream> and <cstring> for string operations.

Define a recursive function printReverseString(const char* str, int n) that takes a pointer to a character array (str) and an integer (n) as arguments.

Base case: If n is 0, return.
Print the last character of the string str[n - 1].
Call the function recursively with str and n - 1 as arguments.
In the main() function:

Declare a character array str to store the input string.
Prompt the user to enter a string and use cin.getline() to read the input string.
Calculate the length of the input string using strlen() and store it in n.
Call the printReverseString() function with str and n as arguments to print the string in reverse.
Print a newline character for formatting.
Return 0 to indicate successful program execution.

Conclusion:
This code successfully prints a given string in reverse using a recursive function. It handles input and calculates the length of the string to ensure correct processing. The recursive approach efficiently reverses the string, demonstrating the power of recursion in solving such problems.

![image](https://github.com/reetikasinghh/Recurssion/assets/139485681/9513d4a1-b44e-45c5-bacb-f7e031fdd6ab)
