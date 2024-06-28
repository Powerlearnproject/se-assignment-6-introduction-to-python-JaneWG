[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15341014&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a an interpreted high-level coding language with dynamic semantic that arer easy to use.

Some of its key features include being easy to use for both beginners and experts. Python is also easy to read in that it uses common language. It is easy to learn and it is also san object oriented progarmming language.

Python is particulary effective in the automaion of tasks, software development and data analysis.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.


To install Python on Windows, follow the followingsteps;
 Go to python.org and go to Downloads
 Select the right version for Windows
 After it has downloaded, go to the downloads folder
 Run the .exe file as admnistrator which will initiate the installation process.
 A message will be sent to verify that the setup was successful.

 To verify that the installation was successsful, got to the command prompt
 Then use python --version command
 if the software installation was a success, you will get the version of the installed software.

 To set up a virtual environment, follow the following steps;
 Go to Git Bash
 Go to the directory you are working on using 
 cd (location of your directory)
 python -- version
 python -m pip install virtualenv
 python -m virtualenv projectname
 source projectname/scripts/activate



3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

Go to Visual Studio Code Editor.
Create a new file named hello.py and choose your directory of choice suh as desktop
Open the file and type in  
print("Hello World")
Go to your terminal
Select new terminal
Choose Bash
Access the directory where you stored hello.py file from Bash
Then run the program using 
python hello.py which will then show 
Hello World.

The basic syntax elements used in the program is
print() which is used to print text in the console


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   
Basic data types in python include 
Boolean data types which are used for a true or false scenario.
Number data types represent numbers and it includes integers, float and complex types
String data types include text such as words
Sequence data types show list of data which include list and tuple data types.
 script for number data types
numbers
a=12
print("The type of variable having value, a, " is ", type(a) )

script for string datatypes
str= "hello"
print(str)

script for boolean datatypes
a = True
# display the value of a
print(a)



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Loops are used to program a list and how each object in the list will be organised.

'if-else' statement
a=30
b=20
if b > a
print ("b is greater than a")

elif a == b
print ("b is equal to a")

else
print ("a is greater than b")

'for' loop
fruits= ["mangoes", "cherries", "oranges"]
for x in fruits
print (x)



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are blocks of code that run specific tasks when called.
Functions help to create code that is repetitive in the program. Functions also help to create code that is complex which helps the developer create the program easily and efficiently. 

Python function with two arguments

add = (lambda x, y): x+y
result= (20, 30)

To call this function, use;
print("Lambda with two argument:",result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.


   Dictionaries are data structres in python that store the needed data in key-value form while lists are used to stre data in linear form.

   Example of a list

   Mylist = [“Kenya”, “Uganda”, “Tanzania”]
print(thislist)

Script for dictionary
thisdict={
“continent”: “Africa”
“country”: “Kenya”
}
print(thisdict)



8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling is handling errors when they occur during programming, which cuase coding process to stop.

 Provide an example of how to use try, except, and finally blocks to handle errors in a 
Python script.
try:
print (x)
except NameError
(“print variable x is not defined”)
except( “something else went wrong”)

finally;
print(“The try…except block is finished”)



9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Both are used to structure and organize code, when python code is contained in a single file, then it is called a module whereas a package is formed by many modules.

To import a module, call 
Import  and the name of file you are importing from
Import ()
To use the math module, call
Import math
x=math.pi
print (x)



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
To read a file, the functions used are open() and read() .
f= open (“hello.py”, “r”)
print (f.read)
 In the console, it will show
Hello, Welcome to hello.py

To write a file, use the functions: open (),  “a” and “w”.

  f =open(“python.py”, “a”)
f.write(now the file has more content!”)
f.close()

In the console, one will see;
Hello! Welcome to hello.py
Now the file has more content!

sources
https://www.scholarhat.com/tutorial/python/python-developer-roadmap
https://www.w3schools.com/python/python_modules.asp
https://www.w3schools.com/python/python_functions.asp
https://www.w3schools.com/python/ref_file_read.asp#:~:text=The%20read()%20method%20returns,which%20means%20the%20whole%20file.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


