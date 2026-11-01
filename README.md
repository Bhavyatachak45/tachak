Practical 1: Student Marks Report (Total, Average and Percentage)
Aim: To write a Python program that reads a student's name, ID, branch and marks of five subjects, and calculate displays the total, average and percentage.
Code:
name input("Enter your Name: ")
reg id input("Enter your ID: ")
brinput("Enter Branch: ")
dbms = float(input("DBMS: "))
os = float(input("OS: "))
pdec float(input("PDEC: "))
ai_ml = float(input("AI_ML: "))
dlca float(input("DLCA: "))
total = dbms + os + pdec + ai ml + dlca
ave total / 5
per total / 500 * 100
print(f"Your Name is {name}\n Your Registration ID is {reg_id}\n
f"Currently you are persuing B.tech in {br}\n"
f"You scored {total} out of 500\n"
"On an Average you scored (ave:.2f}\n"
f f"and you obtained (per:.2f}%")
Output:
Enter your Name: Mahir
Enter your ID: UST2592
Enter Branch: CSE
DBMS: 85
OS: 70
PDEC: 90
AI ML: 92
DLCA: 65
Your Name is Mahir
Your Registration ID is UST2592
Currently you are persuing B.tech in CSE
You scored 402.0 out of 500
On an Average you scored 80.48
and you obtained 80.40%    


Practical 2: Number Guessing Game
Aim: To develop a number guessing game in which the computer picks a random number between 1 and 50, the user keeps guessing with "Too high" / "Too low" hints, and the number of guesses is displayed.
Code:
import random as rd
secret number rd.randint(1, 50)
attempts=0
while True:
guess int(input("Enter a number: "))
attempts attempts + 1
if guess > secret_number:
print("Too high!")
elif guess < secret_number:
print("Too low!")
else:
print("You guessed it!")
print("Number of guesses:", attempts)
break
Output:
Enter a number: 25
Too lowl
Enter a number: 37
Too low!
Enter a number: 43
Too low!
Enter a number: 47
Too lowl
Enter a number: 49
Too highl
Enter a number: 48
You guessed it!
Number of guesses: 6
