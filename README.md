# Basic Calculator Program

## Description
This Python program performs basic arithmetic operations: addition, subtraction, multiplication, and division. The user can choose which operation to perform and input two numbers for the calculation. The program will display the result of the operation in a formatted manner. It continues running in a loop until the user chooses to exit.

## Features
- **Addition**: Adds two numbers and prints the result.
- **Subtraction**: Subtracts the second number from the first and prints the result.
- **Multiplication**: Multiplies two numbers and prints the result.
- **Division**: Divides the first number by the second and prints the result.
- **Exit**: Allows the user to exit the program.

## How to Use
1. Run the program.
2. Choose an operation from the following options:
   - A. Addition
   - B. Subtraction
   - C. Multiplication
   - D. Division
   - E. Exit
3. Enter your choice (e.g., 'A' for Addition).
4. Provide two integer numbers as input when prompted.
5. The program will print the result of the operation in the format:
   ```
   a + b = answer
   ------------------
   ```
6. The program will continue to ask for operations until you choose the 'E' (Exit) option.

## Example
```
A. Addition
B. Subtraction
C. Multiplication
D. Division
E. Exit
Your Choice: A
Addition
First number: 5
Second number: 3
5 + 3 = 8
------------------
```

## Code Explanation
- **Functions**:
  - `add(a, b)`: Adds two numbers and prints the result.
  - `sub(a, b)`: Subtracts the second number from the first and prints the result.
  - `mul(a, b)`: Multiplies two numbers and prints the result.
  - `div(a, b)`: Divides the first number by the second and prints the result.
  
- **Loop**: 
  The program runs inside a `while True` loop, allowing continuous user interaction until the exit option is selected.

- **User Input**: 
  The program asks the user for a choice and two numbers, then performs the corresponding operation.

## Exit Condition
- To stop the program, select the 'E' or 'e' option. The program will terminate with the message "Exit" and quit.

## Requirements
- Python 3.x
