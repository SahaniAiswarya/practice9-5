# practice9-5
#program for basic operations by taking user input of an equation
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=int(input("enter the value of c:"))
x=int(input("enter the value of x:"))
result=a*(x**2)+b*x+c
print("the result of the equation",result)

#swaping with temporarily variable [universal swaping]
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
temp=a
a=b
b=temp
print(a,b)

#swaping with temporarily variable [universal swaping]
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=a
a=b
b=c
print(a,b)

#swaping using arithmetic operators (+,-)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print(a,b)
#swaping using arithmetic operators (*,/)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print(a,b)

#swaping using arithmetic operators (*,/)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print(round(a),round(b))

