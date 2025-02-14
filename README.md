# Project
The addition calculator is a simple tool for quick arithmetic. It lets users sum two numbers or exit. The program runs in a loop, validating inputs and displaying results. Limitations include only handling addition, two numbers at a time, weak input validation, no memory, and a text-based interface. Enhancing it with more operations.


Here’s the input pseudocode: 

while True:
    print("\nAdding Calculator")
    print("1. Add two numbers")
    print("2. Exit")
    
    
    choice = input("Choose an option (1-2): ")
    
    if choice == '2':
        print("Have a safe day.. Goodbye!")
        break  
    
    elif choice == '1':
        
        num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))

        
        total = num1 + num2

        
        print(f"The total is: {total}")
    
    else:
        
        print("Oops. Please enter 1 to add or 2 to exit.")

Here’s the output: 

Adding Calculator
1. Add two numbers
2. Exit
Choose an option (1-2): 1
#Example
Enter the first number: 5
Enter the second number: 10
The total is: 15.0

Adding Calculator
1. Add two numbers
2. Exit
Choose an option (1-2): 2
Have a safe day.. Goodbye!

