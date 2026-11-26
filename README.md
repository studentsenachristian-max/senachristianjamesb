# senachristianjamesb

H

H

H


H


H








import tkinter as tk

print("------------------------------------------")
print("        LEARN PYTHON")
print("------------------------------------------")
print("Learn Python step by step!")
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
                    print("[1] Print and Comments")
                    print("[2] Variables and Constants")
                    print("[3] Data Types")
                    print("[4] Arithmetic Operators")
                    print("[5] Basic Input and Output")
                    print("[6] Back")

                    lesson = input("Choose a lesson: ")

                    if lesson == "1":

                        print()
                        print("LESSON 1: PRINT AND COMMENTS")
                        print()
                        print("The print() function is used to display")
                        print("words, numbers, and other information.")
                        print()
                        print("Example:")
                        print('print("Hello World!")')
                        print()
                        print("Comments are notes in the code.")
                        print("Python does not run comments.")
                        print()
                        print("Example:")
                        print("# This is a comment")
                        print('print("Welcome!")')

                    elif lesson == "2":

                        print()
                        print("LESSON 2: VARIABLES AND CONSTANTS")
                        print()
                        print("A variable is used to store information.")
                        print("Its value can be changed anytime.")
                        print()
                        print("Example:")
                        print('name = "CJ"')
                        print("age = 18")
                        print()
                        print("A constant is a value that should not")
                        print("be changed while the program is running.")
                        print()
                        print("Example:")
                        print("PI = 3.14")

                    elif lesson == "3":

                        print()
                        print("LESSON 3: DATA TYPES")
                        print()
                        print("Data types tell us what kind of")
                        print("information a variable stores.")
                        print()
                        print("String - words or text")
                        print('Example: name = "John"')
                        print()
                        print("Integer - whole numbers")
                        print("Example: age = 18")
                        print()
                        print("Float - numbers with decimal points")
                        print("Example: price = 10.5")
                        print()
                        print("Boolean - True or False")
                        print("Example: is_student = True")

                    elif lesson == "4":

                        print()
                        print("LESSON 4: ARITHMETIC OPERATORS")
                        print()
                        print("Arithmetic operators are used for math.")
                        print()
                        print("+  Addition")
                        print("-  Subtraction")
                        print("*  Multiplication")
                        print("/  Division")
                        print("%  Modulus")
                        print("// Floor Division")
                        print("** Exponent")
                        print()
                        print("Example:")
                        print("a = 10")
                        print("b = 5")
                        print("print(a + b)")
                        print("Answer: 15")

                    elif lesson == "5":

                        print()
                        print("LESSON 5: BASIC INPUT AND OUTPUT")
                        print()
                        print("The input() function is used to get")
                        print("information from the user.")
                        print()
                        print("The print() function displays information.")
                        print()
                        print("Example:")
                        print('name = input("Enter your name: ")')
                        print('print("Hello", name)')
                        print()
                        print("The user can type their name and")
                        print("the program will display a greeting.")

                    elif lesson == "6":
                        break

                    else:
                        print("Invalid choice!")

                    input("\nPress ENTER to continue...")

            elif period == "2":

                while True:

                    print()
                    print("------------ MIDTERM LESSONS ------------")
                    print("[1] Logical Operators")
                    print("[2] If Statement")
                    print("[3] If, Elif and Else")
                    print("[4] Back")

                    lesson = input("Choose a lesson: ")

                    if lesson == "1":

                        print()
                        print("LESSON 1: LOGICAL OPERATORS")
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

                    elif lesson == "2":

                        print()
                        print("LESSON 2: IF STATEMENT")
                        print()
                        print("An if statement is used to check a condition.")
                        print("The code inside it runs when the condition")
                        print("is True.")
                        print()
                        print("Example:")
                        print("age = 18")
                        print("if age >= 18:")
                        print('    print("You are an adult")')

                    elif lesson == "3":

                        print()
                        print("LESSON 3: IF, ELIF AND ELSE")
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

                    elif lesson == "4":
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
                    print("[4] Back")

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

                    elif lesson == "3":

                        print()
                        print("LESSON 3: FOR LOOP")
                        print()
                        print("A for loop is used to repeat code")
                        print("a certain number of times.")
                        print()
                        print("The range() function gives numbers")
                        print("that the loop can use.")
                        print()
                        print("Example:")
                        print("for number in range(1, 6):")
                        print("    print(number)")
                        print()
                        print("This will display numbers from 1 to 5.")

                    elif lesson == "4":
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

        quiz_window = tk.Tk()
        quiz_window.title("Python Learning System - Quiz")
        quiz_window.geometry("550x450")
        quiz_window.resizable(False, False)

        selected_answer = tk.StringVar(master=quiz_window)

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

        title_label = tk.Label(quiz_window, text="PYTHON QUIZ",
                               font=("Arial", 20, "bold"))
        title_label.pack(pady=15)

        number_label = tk.Label(quiz_window, text="Question 1",
                                font=("Arial", 12))
        number_label.pack()

        question_label = tk.Label(quiz_window, text="",
                                  font=("Arial", 14, "bold"),
                                  wraplength=480)
        question_label.pack(pady=20)

        choice_a = tk.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="A",
                                  font=("Arial", 12))
        choice_a.pack(anchor="w", padx=70)

        choice_b = tk.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="B",
                                  font=("Arial", 12))
        choice_b.pack(anchor="w", padx=70)

        choice_c = tk.Radiobutton(quiz_window, text="",
                                  variable=selected_answer, value="C",
                                  font=("Arial", 12))
        choice_c.pack(anchor="w", padx=70)

        feedback_label = tk.Label(quiz_window, text="", font=("Arial", 12))
        feedback_label.pack(pady=15)

        submit_button = tk.Button(quiz_window, text="Submit Answer",
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
