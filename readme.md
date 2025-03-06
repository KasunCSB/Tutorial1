# Add Numbers Program

A simple Python script that prompts the user for two numbers, adds them together, and prints the result.

## Usage

1. Run the script in a Python environment.
2. Enter the first and second numbers when prompted.
3. View the sum displayed as output.

## Code

```python
def add_numbers(a, b):
    return a + b

# Example usage
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result = add_numbers(num1, num2)
print(f"The sum of {num1} and {num2} is: {result}")