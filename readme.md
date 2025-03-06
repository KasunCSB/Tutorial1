# Add Numbers Program

A simple Python script that prompts the user for three numbers, adds them together, and prints the result.

## Usage

1. Run the script in a Python environment.
2. Enter the first, second and third numbers when prompted.
3. View the sum displayed as output.

## Code

```python
def add_numbers(a, b, c):
    return a + b + c

# Example usage
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

result = add_numbers(num1, num2, num3)
print(f"The sum of three numbers is: {result}")