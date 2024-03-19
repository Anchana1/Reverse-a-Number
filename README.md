# Reverse-a-Number
--------------------python-----------------------
print("Enter a Number: ")
num = int(input())

r = 0
while num!=0:
  rem = num%10
  r = rem + (rev*10)
  num = int(num/10)

print("\nReverse =", r)

 output:
 Enter a Number: 266
 Reverse =662
 
