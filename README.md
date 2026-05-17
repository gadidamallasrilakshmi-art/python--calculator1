for i in range(5):
    num1 = int(input("Enter first number: "))
    op = input("Enter operator (+, -, *, /): ")
    num2 = int(input("Enter second number: "))

    if op == "+":
        print(num1 + num2)
    elif op == "-":
        print(num1 - num2)
    elif op == "*":
        print(num1 * num2)
    elif op == "/":
        if num2 != 0:
            print(num1 // num2)  # '//' use chesthe output decimal rakunda normal number vasthundi
        else:
            print("Cannot divide by zero")
    else:
        print("Invalid operator")
