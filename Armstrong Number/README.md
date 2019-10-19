# Armstrong Number
#Armstrong number:  A number is called Armstrong number if it is equal to the sum of the cubes of its #own digits.
#Write a program to generate and check if a number is an Armstrong number.
import random
n=random.random()*2000
copy=n
s=0
while n>=0:
 d=n%10
 s=s+d**3
 n=n//10
if copy==s:
 print("Armstrong")
else:
 print("Not armstrong")







#Built by [Vamsi Krishna][lk]

#[lk]:https://github.com/vamshikrishna10
