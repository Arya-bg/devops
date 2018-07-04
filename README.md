# devops
mkdir Devops
cd Devops, touch Linuxcommand
ls, pwd
mkdir LinuxOS
cd LinuxOS, touch About.txt, nano About.txt
mv LinuxOS Linux
pwd
cd, cd Devops, touch about.txt, nano about.txt
ls
cp/home/user/Devops/about.txt /home/user/Linux/Devops.txt
# linux
mkdir arya, cd arya, nano myself.txt
mkdir reshma, cd reshma, nano herself.txt
du herself.txt
mv myself.txt/home/arya/reshma
chown arya reshma
mkdir multiple, nano abc.txt,nano def.txt,nano ghi.txt
sudo adduser user1,password
sudo adduser user2,password
sudo adduser user3,password
# python
sum of two number,num1=input("Enter the first number"),num2=input("Enter the second number"),sum=num1+num2,print sum
number prime or not,num=input("Enter the number"),if num>1:,for i in range(2,num/2+1):,if(num % i) ==0:,print "The number is not a prime number"
break,else:,print "The number is a prime number",else:,print "The number is not a prime number"
Area of triangle,a=input("Enter the value of height"),b=input("Enter the values of base"),area=0.5*a*b,print area
swap,a=input("Enter the first number"),b=input("Enter the second number"),print "a=", a,print "b=", b,temp=a,a=b,b=temp,print "a", a
print "b", b
quadratic,import cmath,b=input("Enter the values of b"),a=input("Enter the values of a"),c=input("Enter the values of c"),d=(b**2)-(4*a*c)
sol1=(-b+cmath.sqrt(d))/(2*a),sol2=(-b-cmath.sqrt(d))/(2*a),print sol1;,print sol2;
calculator,print("1. Addition");,print("2. Subtraction");,print("3. Multiplication");,print("4. Division");,print("5. Exit");
choice = int(input("Enter your choice: "));,if (choice>=1 and choice<=4):,print("Enter two numbers: ");,num1 = int(input());
num2 = int(input());,if choice == 1:,res = num1 + num2;,print("Result = ", res);,elif choice == 2:,res = num1 - num2;
print("Result = ", res);, elif choice == 3:,res = num1 * num2;,print("Result = ", res);,else:,res = num1 / num2;,print("Result = ", res);
elif choice == 5:,exit();,else:,print("Wrong input..!!");
number posit,nag,or zero,number = int(input("Enter number: ")),if number < 0:,print("The entered number is negative.")
elif number > 0:,print("The entered number is positive."),elif number == 0:,print("Number is zero."),else:,print("The input is not a number")
sum of natural no,num = int(input("Enter the value of n: ")),if num < 0:,print("Enter a positive number"),else:,sum = 0,while(num > 0):
sum += num,num -= 1,print("The sum of first natural number is",sum)
odd or even,num = int(input("Enter any number: ")),flag = num%2,if flag == 0:,print(num, "is an even number"),elif flag == 1:
print(num, "is an odd number"),else:,print("Error, Invalid input")
factorial,def  factorial(num):,if num == 1:,return num,else:, return num * factorial(num - 1),num = int(input("Enter a Number: "))
if num < 0:,print("Factorial cannot be found for negative numbers"),elif num == 0:,print("Factorial of 0 is 1"),else:
print("Factorial of", num, "is: ",factorial(num))
multiplication table,num = int(input("Enter the number:")),print("Multiplication Table of", num),for i in range(1, 11):
print(num,"X",i,"=",num * i)
fibonacci series,nterms = 10,n1 = 0,n2 = 1,count = 0,if nterms <= 0:,print("enter a positive integer"),elif nterms ==1:
print("Fibonacci series upto",nterms,":"),print(n1),else:,print("Fibonacci series upto",nterms,":"),while count < nterms:,print(n1,end=' , ')
nth = n1 + n2, n1 = n2,n2 = nth,count += 1
largest and smallest of number,number1 = int(input('Enter first number : ')),number2 = int(input('Enter the second number : '))
number3 = int(input('Enter the third number : ')),def largest(num1, num2, num3):,if (num1 > num2) and (num1 > num3):
largest_num = num1,elif (num2 > num1) and (num2 > num3):,largest_num = num2,else:,largest_num = num3
print("The largest of the three number is : ",largest_num),def smallest(num1, num2, num3):,if (num1 < num2) and (num1 < num3):
smallest_num = num1,elif (num2 < num1) and (num2 < num3):,smallest_num = num2,else:,smallest_num = num3,print("The smallest of the three number is : ", smallest_num)
largest(number1, number2, number3),smallest(number1, number2, number3)
