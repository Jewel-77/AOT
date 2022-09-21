# AOT
Calculation in python programming 
#find the area of the triangle
a=7
b=8
c=10
#uncomment below to take inputs from user
#a=float(input('enter first side:'))
#b=float(input('enter second side:'))
#c=float(input('enter third side:'))

#calculate the semi-perimeter
s=(a+b+c)/2
#calculate the area
area=(s*(s-a)*(s-b)*(s-c))**0.5
Print (area)
