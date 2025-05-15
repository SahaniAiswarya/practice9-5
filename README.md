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

#print first and last date of a month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday",fday.strftime("%A,%Y-%M-%D"))
print("lastday",lday.strftime("%A,%Y-%M-%D"))

#print first and last date of a month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday",fday.strftime("%A,%Y-%M-%D"))
print("lastday",lday.strftime("%A,%y-%m-%d"))


15/5/25
  num=99
if 99<0:
    print("hi student")

print("india")


  num=99
if num>0:
    print("hi student")

print("india")


  num=-99
if num>0:
    print("hi student")

print("india")



#if condition
person=int(input("enter the age"))
if person>=18:
    print("eligible")


     condition
person=int(input("enter the age"))
limit=18
if person>=limit:
    print("eligible")


    num=int(input("enter the number"))
if num%2==1:
    print("odd",num)

print("after condition exit")


char=input("press any key:")
if char.isalpha():
    print("the user has entered character")
if char.isdigit():
    print("the user has entered digit")
if char.isspace():
    print("the user has entered space")


    #if else condition
person=int(input("enter the age"))
limit=18
if person>=limit:
    print("eligible")
else:
    print("not eligible")


    a=int(input("enter the a value:"))
b=int(input("enter the  value:"))
if a<b:
    small=a
else:
    small=b

print("smallest value",small)


a=int(input("enter the a value:"))
b=int(input("enter the  value:"))
if a>b:
    small=a
else:
    small=b

print("smallest value",small)


ch=input("enter the character")
if ch>='A' and ch<='Z':
    ch=ch.lower()

else:
    ch=ch.upper()

print("converted case of input char:",ch)


num=int(input("enter number"))
if num%4==0 or num%100==0:
    print("leap year",num)

else:
    print("not leap year",num)

print("leap year",num)


num=int(input("enter number"))
if num%4==0 or num%100==0:
    print("leap year")

else:
    print("not leap year")


num=int(input("enter the value:"))
if num==0:
    print("zero")

elif(num>0):
    print("positive")

else:
    print("negative")


    num=int(input("enter the number"))
if num==1:print("sunday")
elif num==2:print("monday")
elif num==3:print("tuesday")
elif num==4:print("wednesday")
elif num==5:print("thursday")
elif num==6:print("friday")
elif num==7:print("saturday")
else:print("wrong input")


ch=input("enter the character")
if ch=='a' or ch=='e' or ch=='i' or ch=='o' or ch=='u':
    print("vowels")
elif ch=='A' or ch=='E' or ch=='I' or ch=='O' or ch=='U':
    print("vowel")
else:
    print("consonents")


    ch=input("enter the character")
if ch=='a' or ch=='e' or ch=='i' or ch=='o' or ch=='u':
    print("small vowels")
elif ch=='A' or ch=='E' or ch=='I' or ch=='O' or ch=='U':
    print("capital vowel")
else:
    print("consonents")
