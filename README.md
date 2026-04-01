 # adityasonth-demo
This is my first Repository 
<br>
Author - Aditya_sonth
SECTION 1: ARITHMETIC OPERATORS ( + - * / // % ** ) 30 Questions

1.Take two integers from user and print their sum.

first_num = int(input("Enter the first number: "))   # 12

second_num = int(input("Enter the second number: ")) # 12

total = first_num + second_num

print("Sum = ", total) # 24

2.Take two integers from user and print their sum.

first_num = int(input("Enter the first number: "))

second_num = int(input("Enter the second number: "))

sub = first_num - second_num

print("Subtraction = ", sub)

3.Take two floats and print multiplication result.

first_num = float(input("Enter the first number: "))

second_num = float(input("Enter the second number: "))

mul = first_num * second_num

print("Multiplication = ", mul)

4.Take two numbers and print division result.

first_num = int(input("Enter the first number: "))

second_num = int(input("Enter the second number: "))

div = first_num / second_num

print("Division = ", div)

5.Take two integers and print floor division result.

first_num = int(input("Enter the first number: "))

second_num = int(input("Enter the second number: "))

div = first_num // second_num

print("Division = ", div)

6.Take two integers and print remainder using %.

first_num = int(input("Enter the first number: "))

second_num = int(input("Enter the second number: "))

rem = first_num % second_num

print("Remainder = ", rem)

7.Take a number and print its square using **.

num = float(input("Enter the number :"))

square = num ** 2

print(f"The square of {num} : {square}")

8.Take a number and print its cube.

num = float(input("Enter the number :"))

square = num ** 3

print(f"The square of {num} : {square}")

#9.Take two numbers and calculate average.

first_num = float(input("Enter the first number: "))

second_num = float(input("Enter the second number: "))

total = first_num + second_num

average = total / 2

print("Average = ",average)

10.Take length and width from user and calculate area.

lenght = float(input("Enter the lenght: "))

width = float(input("Enter the width: "))

area = lenght * width

print("Area = ", area)

11.Take radius and calculate area of circle (3.14 * r * r).

radius = float(input("Enter the radius of the circle: "))

area of circle Pirr

area = 3.14 * radius * radius

print("The area of circle = ",area)

12.Take principal, rate, time and calculate simple interest.

pricipal_value = float(input("Enter the principal value: "))

rate = float(input("Enter the rate: "))

time = int(input("ENter the time(in years): "))

interest = pricipal_value * rate * time

print("Interset = ", interest)

13.Take total marks of 5 subjects and calculate percentage.

marks = [89,34,45,50,60] # Out of 100

Percentage = (sum(marks)/500) * 100

print(f"Percentage = {Percentage:.2f}%") #55.60%

14.Take salary and increase it by 10%.

salary = float(input("Enter the salary: "))

rise_salary = salary * 1.10

print("Salary after the riseing 10%: ", rise_salary)

15.Take a number and divide it by 2 using /= operator.

num = float(input("Enter the number: "))

num /= 2

print(num)

16.Take a number and multiply it by 5 using *= operator.

num = float(input("Enter the number: "))

num *= 5

print(num)

17.Take two numbers and swap them using arithmetic operators.

a = 12

b = 5

print(a, b) # 12 5

a = a + b # 17

b = a - b # 12

a = a - b # 5

print(a, b) # 5 12

18.Take a number and check if it is even using %.

num = int(input("Enter the number: "))

if num % 2 == 0:

print(f"{num} is even")

else:

print(f"{num} is odd")

19.Take a number and check if it is odd using %.

num = int(input("Enter the number: "))

if num % 2 != 0:

print(f"{num} is odd")

else:

print(f"{num} is even")

20.Take total seconds and convert into minutes (use // and %).

seconds = int(input("Enter the seconds"))

seconds = 200

minutes = seconds // 60

remaining_seconds = seconds % 60

print(f"{seconds} seconds = {minutes} minutes and {remaining_seconds} seconds")

21.Take temperature in Celsius and convert to Fahrenheit.

temp = float(input("Enter the temperature in Celsius: "))

Formula : F = (C * 9/5) + 32

formula = (temp * 9/5) + 32

print(f"The temp in Fahrenheit = {formula}°F")

22.Take two numbers and print their power result.

base = 2

exponent = 3

result = base ** exponent

print(result)

23.Take price and discount %, calculate final price.

price = int(input("Enter the Price of the product: "))

discount = float(input("Enter the discount: "))

final_price = price * (1-discount/100)

print(f"The product price after the discount {discount}% = {final_price}")

24.Take a 3-digit number and find sum of digits using % and //.

num = 123

sum = 0

while num > 0:

sum += num % 10  # get last digit

num //= 10       # remove last digit

print(sum)  # Output: 6

25.Take two numbers and print remainder without using % (use formula).

a = 10

b = 3

remainder = a - (a//b) * b

print(f"Reminder = {remainder}")

26.Take a number and print half of it.

num = float(input("ENter the number: "))

half_of_number = num / 2

print("The half of the number: ",half_of_number)

27.Take base and height and calculate area of triangle.

base = float(input("Enter the base: "))

height = float(input("Enter the height: "))

area = (base * height) / 2

print("Area of the tranigle : ",area)

28.Take a number and print its square root using ** 0.5.

num = 49

print(f"The squre root of {num} : ", num ** 0.5)

29.Take monthly salary and calculate yearly salary.

salary = float(input("Enter the montly salary: "))

yearly_salary = salary * 12

print(f"The yearlly salry is :{yearly_salary}")

30.Take total bill and number of people, calculate per person share.

total_bill = 1200

num_people = 4

per_person_share = total_bill / num_people

print(f"Each person pays:{per_person_share} INR") 