# Amstrong-Number-in-python

#Amstrong number simple Ways:
 


n=int(input("Enter the Number"))
s=0
temp=n
a=len(str(n))
while n!=0:
    d=n%10
    s=s+d**a
    n=n//10
if temp==s:
    print("Yes Amstrong number  ")
else:
    print("Not a amstrong Numner")


#Example= 153 =(1*1*1)+(5*5*5)+(3*3*3)
