# Quarter-one-exam-study-guide
A  study guide  for the  quarter one exam
Please copy the code  below and paste it into Jupyter notebook



```
def start():
    print("Hello user this is a study guide for you that I made :D")
    print("if you want the study guide type 1")
    print("in order to cancel type 2 (this is mainly for me but i will leave it in for you:D)")
    user_input =input("TYPE HERE >>>")
    if user_input == "1":
        print('YOU HAVE CHOSEN "STUDY GUIDE" DIRECTING YOU TO "STUDY GUIDE"...')
        Study_guide()
    elif user_input ==  "2":
        print("CANCELING...")
    else:
        print("INVALID INPUT")
        start()
start()

def Study_guide():
    print('Looks like you have chosen "Study guide". The questions will be shown below')
    print("please type the corresponding number linked to the answer")
    Question_one()

def Question_one():
    print("question one")
    print("Write code to create a variable called name and set it to your own name. Then, print the value of name.")
    print('#1: Name = brexton print(Name)')
    print('#2 Name = brexton print("name")')
    print("#3  I want chicken >:(")
    print("#4  Nane == brexton Print name")
   
    user_input = input("type here >>>")
    if user_input == "1":
        print("Correct :D moving on to the next question")
        Question_two()
    else:
        print("incorrect :( Try again")
        Question_one()

def Question_two():
    print("question two")
    print("Create a variable called number and set it to 10. Change the value of number to 20, and then print it.")
    print("#1 Number = 10 Number = 20 print(number)")
    print("#2 Number = 10 Number = 20 print(Number)")
    print("#3 Now i want watermelon >:(")
    print("#4 Number = 20 Number = 10 print(Number)")

    user_input = input("type here >>>")
    if user_input == "2":
        print("correct :D moving on to the next question")
        Question_Three()
    else:
        print("Incorrect :( Try again")
        Question_two()

def Question_Three():
    print("question three")
    print("Write code to create two variables, a = 5 and b = 'three'. Then write the data type of each.")
    print('#1 A = "Five" B = 3')
    print('#2 A = 5 B = Three')
    print('#3 B = 5 A = "Three"')
    print('#4 A = 5 B = "three"')

    user_input =input("type here >>>")
    if user_input == "4":
        print("correct :D Moving on to the next question")
        Section_two()
    else:
        print("incorrect :( Try again")
        Question_Three()

def Section_two():
    print('You have completed section one moving you on to section 2 Tittled "While true loops"')
    print('moveing to "Question Four"') 
    Question_four()

def Question_four():
    print("question four")
    print('Write a while True loop that prints "Looping..."')
    print('#1 a wahailaea taruea  a  priant("loopzing")')
    print('#2 while true    print("looping")')
    print("#3 Whfle tdue Printlooping")

    user_input = input("type here >>>")
    if user_input ==  "2":
        print("correct :D Moving on to the next question")
        Question_five()
    else:
        print("incorrect:( Try again")
        Question_four()

def Question_Five():
    print("question five")
    print('Create a while True loop that asks the user to enter a number. If the number is 7, print "You guessed it!')
    print('#1 give mi coolaide >:(')
    print('#2 wcile true   prqint("enter a number") uzer_input = input() if user_input =="8"    p rint("you got it")')
    print('#3 while true   print("enter a number") user_input = input() if user_input =="7"    print("you got it")')
    user_input = input("type here>>>")
    if user_input == "3":
        print("correct :D moving on to the next question")
        section_three()
    else:
        print("incorrect :( Try again")
        Question_Five()

def section_three():
    print("you have completed section 2 moving you to section 3 titled If/Elf/Else statments")
    print("moving you to question six")
    Question_six()
```
