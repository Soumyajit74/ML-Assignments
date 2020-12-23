# INeuron ML-Assignments
#Assignment 1
#1. 
for i in range (2000, 3201):
    if (i%7==0)&(i%5!=0):
        print(i , end=", ")
        
#2.
f_name = input("Enter first name:")
l_name = input("Enter last name:")
#Concatinating both strings with space
s = f_name+ " " + l_name
print(s)
#Printing in reverse order
print(l_name + " " + f_name)
#printing name inverse order
s[::-1]

#3.
pi=22/7
#Diameter 12cm
d=12
r=d/2
#Volume of sphere
V=4*pi*r**3
print("Volume of the specific sphere is:", V)
