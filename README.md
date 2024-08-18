# DAY-2
#-------
#logical operators are (and,or,not)

#and
T and T = T
T and F = F
print(5>2 and 5==5)#true
print(5>2 and 4==5)#false

#or
----

T or T = T
T or F = T
F or F = F
print(5>2 or 5==5)#true
print(5>2 or 4==5)#true
print(5<2 or 4==5)#false

#not
-----
#if T then F
#if F then T
print(not 5<2)#true
print(not 5>2)#false

#string concatination
#----------------------
#concatination is using (+) operator with strings only
#(str + str)
print("hello"+"world")
#output (helloworld)
#hellohellohellohellohello

#string multiplies
#-------------------

print("hello"*5)
#output (hellohellohellohellohello)

variables
#-----------------
#variables are used to store and manipulate data(example: variable is a container wich holds a data)
x="hello"
print(x)
print(x*5)

#assign operator(=) is used to assign a value to variable
#variable can't start with number (2username,3m,6name)
#variable should not be use (-,(space),)
#variables can use (_) underscore

#---------------------------------------------------------------

#operation using variables
#----------------------------
x=5
y=9
print(x+y)
#----------------------------

#Dynamic typed programming language
#while creating variable we dont want to declare the datatype to assign the value

#--------------------------------------------------------------------------------------------
#Escape sequences
#-----------------
print('hello \nworld')#/n
print('hello \tworld')#/t
#print('i'm /nworld')
#we can use (') inside ('') sentance by using ()
print('i'm\nworld')

#swapping methode
#--------------------------
#methode 01
#----------
a=2
b=3
temp=a
b=a
a=temp
print(a,b)

#methode 02
#----------
a=2
b=3
#a,b=10,5
a,b=b,a
print(a,b)

#--------------

a,b,c=10,5,15
a,b,c=b,c,a
print(a,b,c)

#--------------

#type casting
#-------------

#to change a variable type to another type

a=145
b=12.3
c=True

x=float(a)
y=int(b)
z=str(c)
print(x,y,z)
#----------------------------------------
#type() function
#----------------
#to identify the type of the variable
y=125
print(type(y))
#---------------------------------
x="123.5"
y=float(x)
print(y)
z=int(y)
print(z)
#---------------------------------
'''implace operator
+=
-=
/=
*=
//=
**=
%=
'''
#-----------------------------------
a=10
a+=15 #a=a+15
print(a)
#-------------------------------------
a=10
a-=15 #a=a-15
print(a)
#--------------------------------------

a=10
a/=15 #a=a/15
print(a)
#-------------------------------------- a=10
a*=15 #a=a*15
print(a)
-------------------------------------- a=10
a//=15 #a=a//15
print(a)
-----------------------------------
a=10
a**=15#a=a**15
print(a)
------------------------------------
a=10
a%=15#a=a%15
print(a)
-----------------------------------
