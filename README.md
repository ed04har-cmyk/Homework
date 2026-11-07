# Homework
This is my homework assignment of the 4000 lines of python codes
name = input("Enter your name: ")
print ("Hello " + name + " How may I help you today?")

age = input("What is your age?: ")
print ("Your age is: " + age + " correct?")

print (str(4) + "chan")
print (3 + 4)
print (2 * "di")
print (str(2*2) + "jo")

number = int(input("Enter a number: "))
if number % 4 == 0:
print(f"The number {number} is a multiple of 4")
elif number % 2 == 0:
print(f"The number {number} is an even number" )
else:
print(f"The number {number} is an odd number")

num = int(input("Enter number you want to be dividend: "))
check = int(input("Enter number you want to be divisor: "))
if num % check == 0:
print(f'{check} divides evenly into {num} and the quotient is {num/check}')
else:
print(f"{check} does not divide evenly into {num}")

num1=int(input("give me a number: "))

if num1 % 2 == 0 and num1 % 4 !=0:
print("The given number is Even.")
elif num1 % 4 == 0:
print("Bingo")
else: print("The given number is Odd.")

num2= int(input("Give a number to divide "))
check= int(input("Give a number to divide the previous number: "))
res= num2% check
if res==0:
print(f"Number divides equally")
else: res= num2/ check
print(f"The Output is: {round(res,1)} So it won't get divided evenly")


currentYear = 2026
nameU = input("What is your name?")
ageU = int(input("How old are you?"))
yearAge100 = currentYear - ageU + 100
print("{0}, you will turn 100 years old in the year {1}!".format(nameU,yearAge100))

name = input("Enter your name: ")
print ("Hello " + name + " How may I help you today?")

age = input("What is your age?: ")
print ("Your age is: " + age + " correct?")

print (str(4) + "chan")
print (3 + 4)
print (2 * "di")
print (str(2*2) + "jo")


currentYear = 2026
nameU = input("What is your name?")
ageU = int(input("How old are you?"))
yearAge100 = currentYear - ageU + 100
print("{0}, you will turn 100 years old in the year {1}!".format(nameU,yearAge100))

for row in range (2,7):
    print ("*" * row)


for row in range (1,5): #set it to be the first number for printing 
    for i in range (row): 
        print (str(1), end="")
    print()  #if this part is removed it will turn into one line and not a triangle
    for row in range(1):
        print ("space")

for row in range (1,4):
def score_results(scores:float) -> str:
    grade=""
    if scores >= 90:
        grade="Excellent"
    elif scores >=80:
            grade="good"
    elif scores >=60:
                grade="pass"
    else:
                grade = "fail"


    return grade

score= 63
grade = score_results(score)
print (f"Your score is {score}, and grade is {grade}.")

apple = 3
orange = 5

total_fruits = apple + orange

print("Total number of fruits are:", total_fruits)

hello= "Welcome to the fruit market!"
assist= "how may I assist you today?"

greeting = hello, assist

print(greeting)
greeting = hello + " ,customer " + assist
print(greeting)
def mask_username(name, mask_char="*"):
    if not name:
        return ""
    
    if len(name) <=2:
        return name[0] + mask_char * (len(name) - 1)


user_input= input("enter username:")
def mask_username(name, mask_char="*"):


print("masked name:", mask_char=(user_input))


