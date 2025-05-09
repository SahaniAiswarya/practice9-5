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

#swaping using arithmetic operators xor
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print(round(a),round(b))

#swaping using arithmetic operators xor
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print(a,b)

#area and circumference of circle
r=float(input("enter radius:"))
pi=3.14159
area=pi*r**2
circumference=2*pi*r
print("area of circle",area)
print("circumference of circle",circumference)

#area and circumference of circle
from math import pi
r=float(input("enter radius:"))
area=pi*r**2
circumference=2*pi*r
print("area of circle",area)
print("area of circumference",circumference)

#square root and power
from math import sqrt,pow
n=int(input("enter the value:"))
print(sqrt(n))
print(pow(2,3))

#trigonometric functions
from math import sin,cos,tan,radians
angle=30
print("sin",sin(radians(angle)))
print("cos",cos(radians(angle)))
print("tan",tan(radians(angle)))

from math import floor,ceil
num=float(input("enter the value:"))
print("floor:",floor(num))
print("ceil:",ceil(num))

from math import log,log10,exp
print("natural log:",log(e))
print("log base 10 of 100:",log10(100))
print("e to the power 2:",exp(2))

#date time and calender epoch time
from datetime import datetime
now=datetime.now()
print("current time",now)
print("date:",now.date())
print("time:",now.time())

#calendar
import calendar
print(calendar.month(2004,7))

#calendar with year
import calendar
year=2025
print(calendar.calendar(year))

#calendar leap year
import calendar
leaps=calendar.leapdays(1995,2025)
print(leaps,end='')

#date difference 
from datetime import date
d1=date(2025,5,9)
d2=date(2025,1,1)
diff=d1-d2
print("diffrence in date:",diff.days)

#day abbrevation
from datetime import date
today=date.today()
name=today.strftime("%A")
print("today:",name)
