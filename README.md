# simple-calcy
def add(a,b):
  return a+ b
def sub(a,b):
  return a-b
def mul(a,b):
  return a * b
def div(a,b):
  if b != 0:
    return a/b
  else:
    return "Error: Division by zero"
print("simple calci")
num1 = float(input("Enter first number: "))
operation = input("Enter operation (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operation == '+':
  result = add(num1, num2)
elif operation == '-':
  result = sub(num1, num2)
elif operation == '*':
  result = mul(num1, num2)
elif operation == '/':
  result = div(num1, num2)
else:
  result = "Invalid operation"
print("Result:", result)
