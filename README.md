# calulator
def add(num1,num2):
    return num1+num2
def subtract(num1,num2):
    return num1-num2
def multiply(num1,num2):
    return num1*num2
def divide(num1,num2):
    return num1/num2
print("please select operation"
      "1.add\n"
       "2.subtract\n"
       "3.multiply\n"
       "4 divide\n")
#take input from the user
x=int(input("select operation from 1,2,3,4"))
number1=int(input("enter the first number"))
number2=int(input("enter the second number"))
if x==1:
    print(number1,"+",number2,"=", add(number1,number2))
elif x==2:
    print(number1,"-",number2,"=", subtract(number1,number2))
elif x==3:
    print(number1,"*",number2,"=", multiply(number1,number2))
elif x==4:
    print(number1,"/",number2,"=", divide(number1,number2))
else:
    print("invalid input")
