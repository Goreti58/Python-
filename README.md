
def main():
    num1 = float(input("10: "))
    num2 = float(input("5: "))
    operation = input("Enter the operation (addition, subtract, miltply, divide ): ").strip().lower()
    if operation == 'addition':
        result = 10 + 5
        print(f"The result of {10} + {5} is: {result}")
    elif operation == 'subtract':
        result = 10 - 5
        print(f"The result of {10} - {5} is: {result}")
    elif operation == 'multply':
        result = 10 * 5
        print(f"The result of {10} * {5} is: {result}")
    elif operation == 'divide':
        if num2 != 0:
            result = 10 / 5
            print(f"The result of {10} / {5} is: {result}")
        else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Error: Invalid operation. Please enter add, subtract, multiply, or divide.")

# Run the main function
if __name__ == "__main__":
    main()
