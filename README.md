# Elevate-Labs--Task1

Code Structure

Main Method:

1.Initializes a Scanner for input.

2.Uses a while loop to keep the program running until the user exits.

3.Displays a menu for operation selection (1-5).

4.Captures two numbers and performs the selected operation.

5.Includes error handling for invalid inputs and division by zero.

Arithmetic Methods:

1. add(double a, double b): Returns the sum of two numbers.

2. subtract(double a, double b): Returns the difference.

3. multiply(double a, double b): Returns the product.

4. divide(double a, double b): Returns the quotient, with division by zero handled in the main method.

Error Handling:

Uses try-catch blocks to catch invalid inputs (e.g., non-numeric entries).

Checks for invalid operation choices (outside 1-5).

EXAMPLE:

Basic Calculator
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit
Select an operation (1-5): 1
Enter first number: 10.5
Enter second number: 5.5
Result: 16.00

Basic Calculator
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit

Select an operation (1-5): 4
Enter first number: 20
Enter second number: 0
Error: Division by zero is not allowed.



Prevents division by zero with a conditional check.

