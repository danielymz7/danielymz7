
🎉 Signup To Get Access to the BEST AI Model for Code for FREE
Toggle Sidebar
Blackbox

Terminal

WhatsApp Integration

Vscode
Login

New Chat

Vscode Extension

AI Github Actions

AI Model Page

Android App

Create Chatbot

Personal
Personal
Toggle theme

Edit
Full Screen
Copy code
crie um codigo para fazer uma cauculadora
Edit

Sure, here's a simple calculator code in Python:

python
Save
Full Screen
Copy code
def add(x, y):
   return x + y

def subtract(x, y):
   return x - y

def multiply(x, y):
   return x * y

def divide(x, y):
   if y == 0:
       return "Error! Division by zero is not allowed."
   else:
       return x / y

print("Select operation:")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

while True:
   choice = input("Enter choice(1/2/3/4): ")

   if choice in ('1', '2', '3', '4'):
       num1 = float(input("Enter first number: "))
       num2 = float(input("Enter second number: "))

       if choice == '1':
           print(num1, "+", num2, "=", add(num1, num2))

       elif choice == '2':
           print(num1, "-", num2, "=", subtract(num1, num2))

       elif choice == '3':
           print(num1, "*", num2, "=", multiply(num1, num2))

       elif choice == '4':
           print(num1, "/", num2, "=", divide(num1, num2))
       break
   else:
       print("Invalid Input")
This code will prompt the user to select an operation and enter two numbers. Then it will perform the selected operation on the two numbers and print the result. If the user enters anything other than 1, 2, 3, or 4, the code will print "Invalid Input" and prompt the user again. If the user tries to divide by zero, the code will print an error message.

Is this conversation helpful so far?


Show Diff
Scroll to bottom

Continue

Regenerate

Copy Link to Share Chat

New Chat

Insert Code
Enter a prompt here

Send
By using Blackbox you agree to the 
Terms
 and 
Privacy
.


def add(x, y):
   return x + y

def subtract(x, y):
   return x - y

def multiply(x, y):
   return x * y

def divide(x, y):
   if y == 0:
       return "Error! Division by zero is not allowed."
   else:
       return x / y

print("Select operation:")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

while True:
   choice = input("Enter choice(1/2/3/4): ")

   if choice in ('1', '2', '3', '4'):
       num1 = float(input("Enter first number: "))
       num2 = float(input("Enter second number: "))

       if choice == '1':
           print(num1, "+", num2, "=", add(num1, num2))

       elif choice == '2':
           print(num1, "-", num2, "=", subtract(num1, num2))

       elif choice == '3':
           print(num1, "*", num2, "=", multiply(num1, num2))

       elif choice == '4':
           print(num1, "/", num2, "=", divide(num1, num2))
       break
   else:
       print("Invalid Input")

Close
