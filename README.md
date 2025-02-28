# basic-python-concept
TASK1 DETAIL:-
Explanation:
User Input:

a = int(input("Enter the first number "))
b = int(input("Enter the second number "))
The input() function is used to capture user input. The prompt inside the input() function ("Enter the first number" or "Enter the second number") is displayed to the user.
The input() function always returns the input as a string. Since mathematical operations require numbers, the int() function is used to convert the input string into an integer.
The values entered by the user are stored in the variables a and b.
Addition:
print("addition: ", a + b)
This line calculates the sum of the two integers, a and b, and prints the result.
The result is shown as "addition: <sum>".

Subtraction:
print("addition: ", a - b)
This line calculates the difference between the two integers, a and b, and prints the result.
The result is labeled as "addition", but it is actually a subtraction operation. This is a mistake because the label should reflect the operation performed, like "subtraction".

Multiplication:
print("addition: ", a * b)
This line calculates the product of a and b and prints the result.
Again, the label "addition" is incorrect, as multiplication is being performed.
Division:


print("addition: ", a / b)
This line calculates the quotient of a divided by b and prints the result.
Similarly, the label "addition" is incorrect, as division is being performed here.


TASK2 DETAILS:=
Explanation:
User Input for First Name:

fname = input("Enter your first name: ")
The input() function is used to ask the user for input.
The string "Enter your first name: " is displayed as a prompt to the user.
The function input() waits for the user to type something and press "Enter."
Whatever the user types is returned as a string and stored in the variable fname. This variable now holds the user's first name.
User Input for Last Name:


lname = input("Enter your last name: ")
Similarly, the input() function is used again to ask for the user's last name.
The prompt "Enter your last name: " is displayed, and whatever the user enters is stored as a string in the variable lname.
Output:


print("hello", fname + " " + lname, "Welcome to the python")
The print() function is used to output a message to the user.
The expression fname + " " + lname concatenates (joins) the first name (fname) and the last name (lname) with a space between them. This results in a string containing the full name of the user.
The print() function outputs the string "hello", followed by the concatenated full name (fname + " " + lname), and then the string "Welcome to the python".
The print() function automatically separates each argument by a space, so the output will be in the form: "hello <first name> <last name> Welcome to the python".
Example:
If the user enters:

fname = "John"
lname = "Doe"
The output will be:


hello John Doe Welcome to the python
