# Calculator
Java calculator app

---

# Calculator Program

This is a simple Java-based calculator program that performs basic arithmetic operations, including addition, subtraction, multiplication, and division. The user is prompted to input two numbers and select the desired operation to be performed on those numbers.

## Features

* **Addition**: Adds two numbers.
* **Subtraction**: Subtracts the second number from the first number.
* **Multiplication**: Multiplies two numbers.
* **Division**: Divides the first number by the second number, with a check to prevent division by zero.

## Requirements

* Java 8 or higher is required to run the program.
* A terminal or command prompt to run the program.

## How to Run

1. Download or clone the repository.
2. Open a terminal/command prompt and navigate to the directory containing the `Calculator.java` file.
3. Compile the program by running the following command:

   ```bash
   javac Calculator.java
   ```
4. Run the program using the command:

   ```bash
   java day4.Calculator
   ```
5. Follow the on-screen prompts to enter two numbers and select an operation.

## Example Usage

```
Enter the first number
5
Enter the second number
3
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
1
Result: 8.0
```

## Error Handling

* If the user selects division (Option 4) and attempts to divide by zero, the program will display an error message:
  `Error: Division by zero is not allowed`.

* If an invalid option is chosen, the program will display:
  `Invalid Choice`.

## Code Explanation

1. The program starts by prompting the user to input two numbers.
2. It then presents a menu with four arithmetic operations.
3. Based on the user's choice, the program performs the corresponding operation and displays the result.
4. If the user attempts to divide by zero, the program handles the error by showing a relevant message.
5. If the user enters an invalid option, the program notifies the user.


