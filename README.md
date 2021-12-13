# Basic_Calculator
class Calculator:
    def add(self,a,b):
        return a+b
    
    def sub(self,a,b):
        return a-b
    
    def multiply(self,a,b):
        return a*b
    
    def div(self,a,b):
        return a/b


mycalcus = Calculator()

while True:

    print("1.Add")
    
    print("2.Subtraction")
    
    print("3.Division")
    
    print("4.Multiplication")
    
    print("5.Exit")

    choice = int(input(" Select the Operation: "))

    if choice in (1,2,3,4,5):

        if(choice == 5):
            break

        a = int(input("Enter the 1st number: "))
        b = int(input("Enter the 2nd number: "))

        if (choice == 1):
            print("Result is: ",mycalcus.add(a,b))
        elif (choice == 2):
            print("Result is: ",mycalcus.subtract(a,b))
        elif (choice == 3):
            print("Result is: ",mycalcus.divide(a,b))
        elif (choice == 4):
            print("Result is: ",mycalcus.divide(a,b))

else:

    print("Invalid Input")
