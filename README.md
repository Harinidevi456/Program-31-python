print("Enter the Number: ")
num=int(input())
rev=0
temp=num
while temp>0:
    rem= temp%10
    rev= rem+(rev*10)
    temp= int(temp/10)
if rev==num:
    print("/It is a Palindrome Number")
else:
    print("\nIt is not a Palindrome Number")

Output

Input a string Harinidevi
Letters 10
Digits 0
