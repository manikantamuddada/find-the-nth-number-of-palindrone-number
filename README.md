print('WELCOME! What is your name?')
myName = input()
print('Hello ' + myName + ' Enter random number')
n=int(input("Enter any number: "))
#prime check
f=0
for i in range(2,n):
 if n%i==0:
 print(i)
 f=1
 break
if f==1:
 print(n,"is not a prime")
else:
 print(n,"is prime")
#palindrom number
 x=n
 sum=0
 while x>0:
 r=x%10
 sum=sum*10+r
 x=x//10
 if sum==n:
 print(n,"is a prime palindrom")
 else:
 print(n,"is not a prime palindrom")
