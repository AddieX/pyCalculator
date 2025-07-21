# Simple Python Calculator

A command-line calculator application that performs basic arithmetic operations.

## Features

- Basic arithmetic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (\*)
  - Division (/)
- Input validation
- Error handling for invalid inputs
- Division by zero protection

## Requirements

- Python 3.x

## Usage

1. Run the program:

```bash
python main.py
```

2. Select an operation by entering a number:

   - 1: Addition
   - 2: Subtraction
   - 3: Multiplication
   - 4: Division

3. Enter two numbers when prompted

4. View the result

## Example Usage

```
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice(1/2/3/4): 1
Enter first number: 10
Enter second number: 5
10 + 5 = 15
```

## Error Handling

- Validates numeric input
- Prevents division by zero
- Checks for valid operation selection

## Code Structure

- `add(x, y)`: Performs addition
- `subtract(x, y)`: Performs subtraction
- `multiply(x, y)`: Performs multiplication
- `divide(x, y)`: Performs division with zero check

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
