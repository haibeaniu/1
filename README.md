def add(x, y):
    return x + y
def subtract(x, y):
    return x - y
def multiply(x, y):
    return x * y
def divide(x, y):
    return x / y

print("1 = add\n2 = subtract\n3 = multiply\n4 = divide")
a = input("What do you want me to do ? 1/2/3/4: ")
num1 = float(input("First number: "))
num2 = float(input("Second number: "))

if a == '1':
    print(num1, "+", num2, "=", add(num1, num2))
elif a == '2':
    print(num1, "-", num2, "=", subtract(num1, num2))
elif a == '3':
    print(num1, "*", num2, "=", multiply(num1, num2))
elif a == '4':
    print(num1, ":", num2, "=", divide(num1, num2))
else:
    print("Something is not ok my dude")
