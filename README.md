#senachristianjamesb

import tkinter as cj

R = "\033[91m"
B = "\033[94m"
RESET = "\033[0m"


print("="*45)
print(R + "              WHAT IS PYTHON?" + RESET)
print("="*45)

print()
print("Python is a widely-used programming")
print("language that was created by " + B + "Guido van")
print("Rossum" + RESET + " in " + B + "1991." + RESET)

print()
print(R + "WHY LEARN PYTHON?" + RESET)
print("---------------------------------------------")

print(B + "[1]" + RESET + " Simple and easy to learn")
print("    Great for beginners.")

print()
print(B + "[2]" + RESET + " Readable syntax")
print("    Code looks almost like English.")

print()
print(B + "[3]" + RESET + " Versatile")
print("    Used in AI, web, automation, games, etc.")

print()
print(B + "[4]" + RESET + " Huge community")
print("    Lots of support, tutorials, and libraries.")

print()
print()
print(R + "Lets Learn Python!!" + RESET)
print()
input("Press ENTER to start...")


while True:

    print()
    print("------------------------------------------")
    print("               MAIN MENU")
    print("------------------------------------------")
    print("[1] Lessons")
    print("[2] Take Quiz")
    print("[3] Exit")

    choice = input("Enter your choice: ")

    if choice == "1":

        while True:

            print()
            print("------------------------------------------")
            print("                LESSONS")
            print("------------------------------------------")
            print("[1] Prelim")
            print("[2] Midterm")
            print("[3] Finals")
            print("[4] Back to Main Menu")

            period = input("Choose a period: ")

            if period == "1":

                while True:

                    print()
                    print("------------ PRELIM LESSONS ------------")
                    print("[1] Introduction to Programming")
                    print("[2] Python Programming")
                    print("[3] Python Basic Syntax")
                    print("[4] Print and Comments")
                    print("[5] Variables and Constants")
                    print("[6] Data Types")
                    print("[7] Arithmetic Operators")
                    print("[8] Expressions and PEMDAS")
                    print("[9] Basic Input and Output")
                    print("[10] Back")

                    lesson = input("Choose a lesson: ")

                    if lesson == "1":

                        print()
                        print("LESSON 1: INTRODUCTION TO PROGRAMMING")
                        print()
                        print("Programming is the process of giving")
                        print("instructions to a computer.")
                        print()
                        print("A programming language is a special")
                        print("language that computers understand")
                        print("and use to perform tasks.")
                        print()
                        print("Some programming languages are:")
                        print("1. Python")
                        print("2. C / C++")
                        print("3. Java")
                        print("4. JavaScript")
                        print()
                        print("A program is a set of instructions")
                        print("that tells the computer what to do.")

                    elif lesson == "2":

                        print()
                        print("LESSON 2: PYTHON PROGRAMMING")
                        print()
                        print("Python is a widely-used programming")
                        print("language created by Guido van Rossum")
                        print("in 1991.")
                        print()
                        print("Python is a high-level, interpreted,")
                        print("and general-purpose programming language.")
                        print()
                        print("Why learn Python?")
                        print("1. Simple and easy to learn")
                        print("2. Readable syntax")
                        print("3. Used in many fields")
                        print("4. Has a large community")
                        print()
                        print("Python can be used for websites,")
                        print("automation, games, and many more.")

                    elif lesson == "3":

                        print()
                        print("LESSON 3: PYTHON BASIC SYNTAX")
                        print()
                        print("Syntax is the set of rules on how")
                        print("to correctly write a Python program.")
                        print()
                        print("Python is case-sensitive.")
                        print("Uppercase and lowercase letters are different.")
                        print()
                        print("Example:")
                        print('name = "John"')
                        print("print(name)")
                        print()
                        print("Indentation means adding spaces")
                        print("before a line of code.")
                        print("It is used to show which code belongs")
                        print("inside a block.")
                        print()
                        print("Example:")
                        print("age = 18")
                        print("if age >= 18:")
                        print('    print("Adult")')

                    elif lesson == "4":

                        print()
                        print("LESSON 4: PRINT AND COMMENTS")
                        print()
                        print("The print() function is used to display")
                        print("words, numbers, and other information.")
                        print()
                        print("Example:")
                        print('print("Hello World!")')
                        print("print(100)")
                        print()
                        print("Text or string must have quotation marks.")
                        print("Numbers can be printed without quotes.")
                        print()
                        print("You can also print many variables.")
                        print("Example:")
                        print('a = "I"')
                        print('b = "LOVE"')
                        print('c = "CCST"')
                        print("print(a, b, c)")
                        print()
                        print("The + sign can join text together.")
                        print('print("I " + "LOVE " + "CCST")')
                        print()
                        print("Comments are notes in the code.")
                        print("Python ignores comments.")
                        print()
                        print("Single-line comment:")
                        print("# This is a comment")
                        print()
                        print("Multi-line comment:")
                        print('"""')
                        print("This is a multi-line comment.")
                        print('"""')

                    elif lesson == "5":

                        print()
                        print("LESSON 5: VARIABLES AND CONSTANTS")
                        print()
                        print("A variable is a named storage location")
                        print("used to keep data in a program.")
                        print("Its value can change while the program")
                        print("is running.")
                        print()
                        print("Example:")
                        print('name = "CJ"')
                        print("age = 18")
                        print()
                        print("The equal sign is called assignment")
                        print("operator. It gives a value to a variable.")
                        print()
                        print("Example:")
                        print('school = "CCST"')
                        print("print(school)")
                        print()
                        print("Variable names can be short or descriptive.")
                        print("Examples: x, y, age, carname, total_volume")
                        print()
                        print("Variable naming rules:")
                        print("1. Must start with a letter or underscore.")
                        print("2. Cannot start with a number.")
                        print("3. No spaces or special characters.")
                        print("4. Variable names are case-sensitive.")
                        print()
                        print("A constant is a value that should not")
                        print("be changed. We usually write it in uppercase.")
                        print()
                        print("Example:")
                        print("PI = 3.14")

                    elif lesson == "6":

                        print()
                        print("LESSON 6: DATA TYPES")
                        print()
                        print("Data types tell Python what kind of")
                        print("information a variable stores.")
                        print()
                        print("int - whole numbers")
                        print("Example: age = 18")
                        print()
                        print("float - numbers with decimal points")
                        print("Example: price = 10.5")
                        print()
                        print("str - words or text inside quotation marks")
                        print('Example: name = "John"')
                        print()
                        print("bool - True or False values")
                        print("Example: passed = True")
                        print()
                        print("Example:")
                        print('name = "Maria"')
                        print("age = 20")
                        print("grade = 89.5")
                        print("is_enrolled = True")
                        print()
                        print("print(name)")
                        print("print(age)")
                        print("print(grade)")
                        print("print(is_enrolled)")

                    elif lesson == "7":

                        print()
                        print("LESSON 7: ARITHMETIC OPERATORS")
                        print()
                        print("Arithmetic operators are symbols used")
                        print("to perform mathematical calculations.")
                        print()
                        print("+  Addition")
                        print("   Example: 5 + 3 = 8")
                        print()
                        print("-  Subtraction")
                        print("   Example: 10 - 4 = 6")
                        print()
                        print("*  Multiplication")
                        print("   Example: 7 * 2 = 14")
                        print()
                        print("/  Division")
                        print("   Example: 15 / 3 = 5.0")
                        print()
                        print("// Floor Division")
                        print("   Example: 17 // 3 = 5")
                        print()
                        print("%  Modulus")
                        print("   Gets the remainder.")
                        print("   Example: 10 % 3 = 1")
                        print()
                        print("** Exponentiation")
                        print("   Raises a number to a power.")
                        print("   Example: 2 ** 3 = 8")

                    elif lesson == "8":

                        print()
                        print("LESSON 8: EXPRESSIONS AND PEMDAS")
                        print()
                        print("An expression is a combination of values,")
                        print("variables, and operators that gives a result.")
                        print()
                        print("Example:")
                        print("a = 10")
                        print("b = 5")
                        print("result = a + b")
                        print('print("The result is:", result)')
                        print()
                        print("PEMDAS tells the order of operations.")
                        print()
                        print("P - Parentheses")
                        print("E - Exponents")
                        print("MD - Multiplication and Division")
                        print("AS - Addition and Subtraction")
                        print()
                        print("Example:")
                        print("answer = 2 + 3 * 4")
                        print("The answer is 14 because multiplication")
                        print("is done before addition.")
                        print()
                        print("You can use parentheses to change")
                        print("the order of the calculation.")
                        print()
                        print("Example:")
                        print("answer = (2 + 3) * 4")
                        print("The answer is 20.")

                    elif lesson == "9":

                        print()
                        print("LESSON 9: BASIC INPUT AND OUTPUT")
                        print()
                        print("The input() function gets information")
                        print("from the user.")
                        print()
                        print("The print() function displays information.")
                        print()
                        print("Example:")
                        print('name = input("Enter your name: ")')
                        print('print("Hello", name)')
                        print()
                        print("The input() function gives a string.")
                        print("Use int() for whole numbers.")
                        print("Use float() for decimal numbers.")
                        print()
                        print("Example:")
                        print('age = int(input("Enter age: "))')
                        print('price = float(input("Enter price: "))')
                        print()
                        print("You can also display variables using")
                        print("print() and f-strings.")
                        print()
                        print("Example:")
                        print('print(f"Your age is {age}")')

                    elif lesson == "10":
                        break

                    else:
                        print("Invalid choice!")

                    input("\nPress ENTER to continue...")

            elif period == "2":

                while True:

                    print()
                    print("------------ MIDTERM LESSONS ------------")
                    print("[1] Relational Operators")
                    print("[2] Logical Operators")
                    print("[3] Conditional Statements")
                    print("[4] If Statement")
                    print("[5] If, Elif and Else")
                    print("[6] Nested If Statement")
                    print("[7] Back")

                    lesson = input("Choose a lesson: ")

                    if lesson == "1":

                        print()
                        print("LESSON 1: RELATIONAL OPERATORS")
                        print()
                        print("Relational operators are used to compare")
                        print("two values. The result is True or False.")
                        print()
                        print("==  Equal to")
                        print("!=  Not equal to")
                        print(">   Greater than")
                        print("<   Less than")
                        print(">=  Greater than or equal to")
                        print("<=  Less than or equal to")
                        print()
                        print("Example:")
                        print("a = 10")
                        print("b = 5")
                        print("print(a > b)")
                        print("Answer: True")

                    elif lesson == "2":

                        print()
                        print("LESSON 2: LOGICAL OPERATORS")
                        print()
                        print("Logical operators are used to combine")
                        print("or reverse conditions.")
                        print()
                        print("AND - True when both conditions are True.")
                        print("OR - True when at least one is True.")
                        print("NOT - Reverses the result.")
                        print()
                        print("Example:")
                        print("age = 18")
                        print("print(age >= 18 and age <= 30)")
                        print()
                        print("AND example:")
                        print("True and True = True")
                        print("True and False = False")
                        print()
                        print("OR example:")
                        print("True or False = True")
                        print("False or False = False")
                        print()
                        print("NOT example:")
                        print("not True = False")
                        print("not False = True")

                    elif lesson == "3":

                        print()
                        print("LESSON 3: CONDITIONAL STATEMENTS")
                        print()
                        print("Conditional statements are used to make")
                        print("decisions in a Python program.")
                        print()
                        print("The program checks if a condition is True")
                        print("or False before running a code.")
                        print()
                        print("Common conditional statements:")
                        print("1. if")
                        print("2. if-else")
                        print("3. if-elif-else")
                        print("4. nested if")

                    elif lesson == "4":

                        print()
                        print("LESSON 4: IF STATEMENT")
                        print()
                        print("An if statement is used to check a condition.")
                        print("The code inside it runs when the condition")
                        print("is True.")
                        print()
                        print("Example:")
                        print("age = 18")
                        print("if age >= 18:")
                        print('    print("You are an adult")')
                        print()
                        print("If the condition is False, the code")
                        print("inside the if statement will not run.")

                    elif lesson == "5":

                        print()
                        print("LESSON 5: IF, ELIF AND ELSE")
                        print()
                        print("If checks the first condition.")
                        print("Elif checks another condition.")
                        print("Else runs when the other conditions")
                        print("are False.")
                        print()
                        print("Example:")
                        print("grade = 85")
                        print()
                        print("if grade >= 90:")
                        print('    print("Excellent")')
                        print("elif grade >= 75:")
                        print('    print("Passed")')
                        print("else:")
                        print('    print("Failed")')

                    elif lesson == "6":

                        print()
                        print("LESSON 6: NESTED IF STATEMENT")
                        print()
                        print("A nested if is an if statement inside")
                        print("another if statement.")
                        print()
                        print("It is used when we need to check")
                        print("another condition inside a condition.")
                        print()
                        print("Example:")
                        print("gender = 'M'")
                        print("age = 21")
                        print()
                        print("if gender == 'M':")
                        print("    if age >= 21:")
                        print('        print("Male Debutant")')
                        print("    else:")
                        print('        print("Not a debutant yet")')
                        print("else:")
                        print('    print("Not male")')

                    elif lesson == "7":
                        break

                    else:
                        print("Invalid choice!")

                    input("\nPress ENTER to continue...")

            elif period == "3":

                while True:

                    print()
                    print("------------- FINALS LESSONS -------------")
                    print("[1] Introduction to Iteration")
                    print("[2] While Loop")
                    print("[3] For Loop")
                    print("[4] Range Function")
                    print("[5] Counting, Odd and Even Numbers")
                    print("[6] Back")

                    lesson = input("Choose a lesson: ")

                    if lesson == "1":

                        print()
                        print("LESSON 1: INTRODUCTION TO ITERATION")
                        print()
                        print("Iteration means repeating a set of")
                        print("instructions in a program.")
                        print()
                        print("Loops help us repeat code without")
                        print("writing the same instructions many times.")
                        print()
                        print("Python has two common loops:")
                        print("1. While Loop")
                        print("2. For Loop")

                    elif lesson == "2":

                        print()
                        print("LESSON 2: WHILE LOOP")
                        print()
                        print("A while loop repeats code as long as")
                        print("the condition is True.")
                        print()
                        print("Example:")
                        print("number = 1")
                        print()
                        print("while number <= 5:")
                        print("    print(number)")
                        print("    number = number + 1")
                        print()
                        print("The loop stops when the condition")
                        print("becomes False.")
                        print()
                        print("You can also use += to add a value.")
                        print("Example:")
                        print("number += 1")

                    elif lesson == "3":

                        print()
                        print("LESSON 3: FOR LOOP")
                        print()
                        print("A for loop is used to repeat code")
                        print("a certain number of times.")
                        print()
                        print("Example:")
                        print("for number in range(1, 6):")
                        print("    print(number)")
                        print()
                        print("This will display numbers from 1 to 5.")
                        print()
                        print("The loop repeats for every number")
                        print("given by the range() function.")

                    elif lesson == "4":

                        print()
                        print("LESSON 4: RANGE FUNCTION")
                        print()
                        print("The range() function gives a sequence")
                        print("of numbers that can be used in a loop.")
                        print()
                        print("range(stop)")
                        print("Starts at 0 and stops before the number.")
                        print("Example: range(5) gives 0, 1, 2, 3, 4")
                        print()
                        print("range(start, stop)")
                        print("Starts at the start number and stops")
                        print("before the stop number.")
                        print("Example: range(1, 6) gives 1 to 5")
                        print()
                        print("range(start, stop, step)")
                        print("Step tells how many numbers to skip.")
                        print("Example: range(2, 11, 2)")
                        print("Output: 2, 4, 6, 8, 10")
                        print()
                        print("Example code:")
                        print("for x in range(1, 6):")
                        print("    print(x)")

                    elif lesson == "5":

                        print()
                        print("LESSON 5: COUNTING, ODD AND EVEN NUMBERS")
                        print()
                        print("A counter is a variable that changes")
                        print("its value while a loop is running.")
                        print()
                        print("Example:")
                        print("number = 1")
                        print("while number <= 5:")
                        print("    print(number)")
                        print("    number = number + 1")
                        print()
                        print("The modulus operator (%) can check")
                        print("if a number is odd or even.")
                        print()
                        print("Even number example:")
                        print("number = 4")
                        print("if number % 2 == 0:")
                        print('    print("Even Number")')
                        print()
                        print("Odd number example:")
                        print("number = 5")
                        print("if number % 2 != 0:")
                        print('    print("Odd Number")')

                    elif lesson == "6":
                        break

                    else:
                        print("Invalid choice!")

                    input("\nPress ENTER to continue...")

            elif period == "4":
                break

            else:
                print("Invalid choice!")


    elif choice == "2":

        print()
        print("------------------------------------------")
        print("                  QUIZ")
        print("------------------------------------------")
        print("[1] Prelim Quiz")
        print("[2] Midterm Quiz")
        print("[3] Finals Quiz")
        print("[4] Back")

        quiz_choice = input("Choose a quiz: ")

        questions = []
        choices = []
        answers = []

        if quiz_choice == "1":

            questions = [
                "Which function displays information?",
                "Which symbol is used for comments?",
                "Which data type stores whole numbers?",
                "Which operator is used for multiplication?",
                "Which function gets user input?"
            ]

            choices = [
                ["A. input()", "B. print()", "C. int()"],
                ["A. #", "B. //", "C. **"],
                ["A. String", "B. Float", "C. Integer"],
                ["A. +", "B. *", "C. /"],
                ["A. print()", "B. input()", "C. float()"]
            ]

            answers = ["B", "A", "C", "B", "B"]

        elif quiz_choice == "2":

            questions = [
                "Which operator needs both conditions to be True?",
                "Which operator needs only one condition to be True?",
                "Which statement checks a condition?",
                "Which statement checks another condition?",
                "What runs when all conditions are False?"
            ]

            choices = [
                ["A. OR", "B. NOT", "C. AND"],
                ["A. OR", "B. AND", "C. NOT"],
                ["A. if", "B. print", "C. input"],
                ["A. else", "B. elif", "C. while"],
                ["A. if", "B. elif", "C. else"]
            ]

            answers = ["C", "A", "A", "B", "C"]

        elif quiz_choice == "3":

            questions = [
                "What does iteration mean?",
                "Which loop repeats while a condition is True?",
                "Which loop is commonly used with range()?",
                "What happens when a while condition becomes False?",
                "Which function gives a sequence of numbers?"
            ]

            choices = [
                ["A. Repeating instructions", "B. Deleting code", "C. Printing text"],
                ["A. For loop", "B. While loop", "C. If statement"],
                ["A. If", "B. While", "C. For"],
                ["A. It continues forever", "B. It stops", "C. It restarts"],
                ["A. input()", "B. range()", "C. print()"]
            ]

            answers = ["A", "B", "C", "B", "B"]

        elif quiz_choice == "4":
            continue

        else:
            print("Invalid choice!")
            continue

        question_number = 0
        score = 0
        answered = False

        quiz_window = cj.Tk()
        quiz_window.title(" CJ Quiz")
        quiz_window.geometry("550x450")
        quiz_window.resizable(False, False)

        selected_answer = cj.StringVar(master=quiz_window)

        def show_question():

            selected_answer.set("")

            question_label.config(text=questions[question_number])

            choice_a.config(text=choices[question_number][0])
            choice_b.config(text=choices[question_number][1])
            choice_c.config(text=choices[question_number][2])

            feedback_label.config(text="")
            submit_button.config(text="Submit Answer")

            number_label.config(
                text="Question " + str(question_number + 1)
                + " / " + str(len(questions))
            )

        def check_answer():

            global question_number
            global score
            global answered

            if answered == False:

                answer = selected_answer.get().upper()

                if answer == "":
                    feedback_label.config(text="Please select an answer!")
                    return

                if answer == answers[question_number]:

                    score = score + 1
                    feedback_label.config(text="Correct answer!")

                else:

                    feedback_label.config(
                        text="Wrong! Correct answer: " + answers[question_number]
                    )

                answered = True
                submit_button.config(text="Next Question")

            else:

                question_number = question_number + 1
                answered = False

                if question_number < len(questions):

                    show_question()

                else:

                    question_label.config(
                        text="QUIZ FINISHED!\n\nYour Score: "
                        + str(score) + " / " + str(len(questions))
                    )

                    number_label.config(text="Your Result")

                    choice_a.pack_forget()
                    choice_b.pack_forget()
                    choice_c.pack_forget()

                    feedback_label.config(text="Thank you for answering!")

                    submit_button.pack_forget()

        title_label = cj.Label(quiz_window, text="PYTHON QUIZ",
                               font=("Arial", 20, "bold"))
        title_label.pack(pady=15)

        number_label = cj.Label(quiz_window, text="Question 1",
                                font=("Arial", 12))
        number_label.pack()

        question_label = cj.Label(quiz_window, text="",
                                  font=("Arial", 14, "bold"),
                                  wraplength=480)
        question_label.pack(pady=20)

        choice_a = cj.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="A",
                                  font=("Arial", 12))
        choice_a.pack(anchor="w", padx=70)

        choice_b = cj.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="B",
                                  font=("Arial", 12))
        choice_b.pack(anchor="w", padx=70)

        choice_c = cj.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="C",
                                  font=("Arial", 12))
        choice_c.pack(anchor="w", padx=70)

        feedback_label = cj.Label(quiz_window, text="", font=("Arial", 12))
        feedback_label.pack(pady=15)

        submit_button = cj.Button(quiz_window, text="Submit Answer",
                                  font=("Arial", 12),
                                  command=check_answer)
        submit_button.pack(pady=10)

        show_question()

        quiz_window.mainloop()


    elif choice == "3":

        print()
        print("------------------------------------------")
        print("Thank you for using Python Learning System!")
        print("Keep learning and keep practicing!")
        print("------------------------------------------")
        break

    else:

        print("Invalid choice! Please try again.")
