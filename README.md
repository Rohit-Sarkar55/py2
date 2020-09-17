# py2

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number: "))
 
if (num1 > num2) and (num1 > num3):
	g=num1
elif(num2 > num1)and(num2 > num3):
	g=num2
elif(num3 > num1)and(num3 > num2):
	g=num3
if(g==num1):
	if(num2<num3):
		s=num2
	else:
		s=num3
if(g==num2):
	if(num1<num3):
		s=num1
	else:
		s=num3
if(g==num3):
	if(num1<num2):
		s=num1
	else:
		s=num2
print(g)
print(s)

[17/09, 20:31] Rohit Sarkar: x=int(input("Enter a number"))
y=int(input("Enter a number"))
if x>y:
    print("greater value is",x)
elif y>x:
    print("greater value is",y)
else:
    print("Equal")

[17/09, 20:32] Rohit Sarkar: a=int(input("Enter number of hours"))
b=float(input("Enter rate"))
if (a>40):
	print("Amount will be",(a*b*1.5))
else:
	print("Amount will be",(a*b))

[17/09, 20:32] Rohit Sarkar: x=float(input("Enter the degree\n"))
y=input("Enter the C or F\n")
if y=='C' or y=='c':
	temp=((9*x)/5)+32
else:
	temp=((x-32)*5)/9
print(temp)

[17/09, 20:33] Rohit Sarkar: x=int(input("Enter the number\n"))
if x>0:
	print("Positive number\n")
else:
	print("Negative number\n")

[17/09, 20:33] Rohit Sarkar: x=int(input("Enter the number\n"))
if x%2==0:
	print("Even number\n")
else:
	print("Odd number\n")

[17/09, 20:33] Rohit Sarkar: num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
    sum = sum + (temp%10)**3 
    temp = int(temp/10)
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")

[17/09, 20:33] Rohit Sarkar: n = float(input("Enter the grade in between 0.0 to 1.0\n"))
if n<0.0 and n>1.0:
	print("Error")
elif n<0.6:
	print("F")
elif n>=0.6 and n<=0.69:
	print("D")
elif n>=0.7 and n<=0.79:
	print("C")
elif n>=0.8 and n<=0.89:
	print("B")
elif n>=0.9 and n<=1.0:
	print("A")

[17/09, 20:33] Rohit Sarkar: n = input("Enter hour\n")
y=input("Enter rate\n")
try:
  print(n)
  print(y)
except:
  print("An exception occurred")
