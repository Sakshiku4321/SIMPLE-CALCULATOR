# SIMPLE-CALCULATOR
def add(p,q):
    return(x+y)
def subtract(p,q):
    return(x-y)
def multiply(p,q):
    return(x*y)
def divide(p,q):
    return(x/y)
x=int(input("Enter first number: "))
y=int(input("Enter second number: "))

print("1 - Addition")
print("2 - Subtraction")
print("3 - Multiplication")
print("4 - Division")
print("5 - Exit")

while(True):
    choice=int(input("Choose an operation  "))
    if(choice in [1,2,3,4,5]):
        if (choice==1):
            print(add(x,y))
        elif(choice==2):
            print(subtract(x,y))
        elif(choice==3):
            print(multiply(x,y))
        elif(choice==4):
            print(divide(x,y))
        elif(choice==5):
            print("Thank you :)")
            exit()
    else:
        print("Invalid operation")
