<h2>Intern</h2>
<b>Name:</b> SHAIK ASIF<br>
<b>Collage:</b> NRI Institute of technology<BR>
<b>Roll No:</b>22KP1A44A9<BR>
<b>Company:</b>CODTECH IT SOLUTIONS<BR>
<b>ID:</b>CT4PP3591<BR>
<b>Domain:</b>PYTHON PROGRAMMING<BR>
<b>Duration:</b> JULY TO AUGUST 2024<BR>
<b>Mentor:</b>SRAVANI GOUNI<BR>

<h2>Simple Calculator Project Overview</h2>
<b>Sample Code:</b><br>
<pre>
  
#Define a function for each operation
def add(x, y):
  return x + y

def sub(x, y):
  return x - y

def mul(x, y):
  return x * y

def div(x, y):
  if y == 0:
    return "Error: Division by zero is not allowed"
  return x / y
  
#Main program
print("Simple Calculator")
print("----------------")

#Get the two numbers from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

#Get the operation from the user
print("Choose an operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")
op = int(input("Enter your choice (1/2/3/4): "))

#Perform the operation
if op == 1:
  result = add(num1, num2)
elif op == 2:
  result = sub(num1, num2)
elif op == 3:
  result = mul(num1, num2)
elif op == 4:
  result = div(num1, num2)
else:
  result = "Error: Invalid operation"
  
#Display the result
print("Result:", result)
</pre><br>
# OutPut
![image](https://github.com/user-attachments/assets/8265ab10-35bb-4602-8141-8c09549c13e9)


<br>
<h2>Objective:</h2><br>
The objective of this project is to create a basic calculator that can perform fundamental arithmetic operations such as addition, subtraction, multiplication, and division. This project demonstrates the use of Python programming for developing a user-friendly and functional calculator.<br>

<h2>Features:</h2>

<b>User Interface:</b><br>
The calculator provides a simple text-based user interface.
Users can input two numbers and choose an operation to perform.<bR>

<b>Arithmetic Operations:</b><br>
Addition: Adds two numbers.
Subtraction: Subtracts the second number from the first.
Multiplication: Multiplies two numbers.
Division: Divides the first number by the second, with a check to prevent division by zero.<br>

<b>Error Handling:</b><br>
Handles invalid inputs and prompts the user to enter valid numbers.
Includes error messages for division by zero and other invalid operations.<br>

<h2>Implementation:</h2>
The project is implemented using basic Python programming constructs, such as functions, conditional statements, and loops. Below is a brief outline of the code structure:
<br>

<b>Function Definitions:</b><br>
Functions for each arithmetic operation: add(), subtract(), multiply(), and divide().
A function to display the menu and get the user's choice of operation.
A main function to drive the program and handle user input and output.<br>

<b>User Input and Output:</b><br>
The program prompts the user to enter two numbers.
It displays a menu of operations and asks the user to choose one.
Based on the user's choice, it calls the corresponding function to perform the operation and displays the result.<br>

<b>Main Loop:</b><br>
The program runs in a loop, allowing the user to perform multiple calculations until they choose to exit.<br>

<h2>Conclusion:</h2><br>
This simple calculator project is an excellent way to practice and understand basic Python programming concepts. It can be expanded with additional features, such as more complex operations, a graphical user interface (GUI), or enhanced error handling.



