# Conditional Statments
Conditional statements are used to control the flow of execution in a program based on specific conditions. They allow programs to execute different blocks of code depending on whether a condition evaluates to True or False.

# Types
 * If Statement
   If statement is used to execute a block of code only when a specified condition evaluates to True.
   Example:
   age = 20
   if age >= 18:
    print("Eligible to vote.")

 * If else Statement
   If Else statement is used to execute one block of code when the condition is True and another block when the condition is False.
   Example:
   age = 10
   if age <= 12:
    print("Travel for free.")
   else:
    print("Pay for ticket.")

 * If-elif-else Statement
   Elif statement is used to check multiple conditions in a program. It executes a block of code when its condition evaluates to True         after previous conditions evaluate to False.
   Example:
   marks = 75
   if marks >= 90:
    print("Grade A")
   elif marks >= 80:
    print("Grade B")
   elif marks >= 70:
    print("Grade C")
   else:
    print("Grade D")

 * Nested if-else Statement
   Nested if-else statement is an if-else statement placed inside another if or else block. It is used to check conditions within          another condition.
   Example:
   age = 70
   is_member = True
   if age >= 60:
    if is_member:
        print("30% senior discount!")
    else:
        print("20% senior discount.")
   else:
    print("Not eligible for a senior discount.")

 * Match-Case Statement
   Match-Case statement is used to compare a value against multiple patterns and execute the matching block of code. It is similar to      the switch-case statement available in other programming languages.
   Example:
   number = 2
   match number:
    case 1:
        print("One")
    case 2 | 3:
        print("Two or Three")
    case _:
        print("Other number")

# Key Learnings
Learn how different statements work
