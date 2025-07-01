# 🧮 Simple Calculator (If-Else Based)

A beginner-friendly Python calculator that uses `if-else` statements to perform basic arithmetic operations based on user input.

# Simple calculator with if-else statements

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
operation = input("Enter operation (+, -, *, /): ")

if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error: Division by zero"
else:
    result = "Error: Invalid operation"

print("Result:", result)
