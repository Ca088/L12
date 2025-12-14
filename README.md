def wishes(name):
    print("Hello ",name)
    print("Good morning! Welcome to python class \n")

wishes("Raj")
wishes("Ravi")
wishes("Ramesh")

def weather(w,c):
    print("Todays weather is ",w,"" "\n")
    print("Its too much",c,"\n")
weather('Sunny',"hot")
weather("rainy","cold")
weather("cloudy","cool")


def add(num1,num2):
    return num1+num2
def substract(num1,num2):
    return num1-num2
try:
    print("Choice 1 : Addition\nChoice 2: Substraction")
    choice=int(input("Enter your choice: "))
except:
    print("Enter a number pls")
n1=int(input("Enter your first num: "))
n2=int(input("Enter your second num: "))


if choice==1:
    print(add(n1,n2))
elif choice==2:
    print(substract(n1,n2))
else:
    print("Please enter a num")
