# Assignment1
2)#Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both #included). The numbers obtained should be printed in a comma-separated sequence on a single line.
l=[]
for x in range(2000,3201):
    if (x%7==0) and (x%5!=0):
        l.append((x))
print(l)

3)fname = input("Input your First Name : ")
  lname = input("Input your Last Name : ")
  print ("Hello  " + lname + " " + fname)



4)Write a Python program to find the volume of a sphere with diameter 12 cm.
Formula: V=4/3 * π * r
pi = 3.1415926535897931
r= 6.0
V= 4.0/3.0*pi* r**3
print('The volume of the sphere is: ',V)  

#output for this question is given as output3 image
