1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a programming language known for its readability and simplicity. It has a standard library and supports multiple programming paradigms. Key features include:Easy-to-read syntax,Dynamic typing, Automatic memory management

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   a. Download the installer
   b. Run the installer and add it in the path in the system variable
   c. Follow the installation steps
   To verify run `python --version`
   Setting up a virtual environment run:
   `python -m venv myenv
   source myenv\Scripts\activate`

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   `print("Hello World!")`

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic data types include:
   int: integer values,
   float: Decimal numbers
   str: strings
   scripts include:
   `
   age = 35 #integer
   height = 6.3 #Float
   name = Gideon #string

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional statements allow you to execute code based on conditions.
   age = 18
   if age >= 18:
      print("You are an adult")
   else:
      print("You are not an adult")

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions are blocks of reusable code that perform a specific task. They help in organizing code, making it more modular and easier to read and maintain.
   def add(a, b):
    return a + b

   result = add(3, 5)
   print(result)  # Output: 8


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists are ordered collections of items accessed by index.
   Dictionaries are unordered collections of key-value pairs accessed by key.
   # List
   numbers = [1, 2, 3, 4, 5]
   numbers.append(6)
   print(numbers)

   # Dictionary
   person = {"name": "Alice", "age": 25}
   person["age"] = 26
   print(person)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
     
   Exception handling is used to manage errors in a controlled way, preventing the program from crashing.
    try:
      result = 10 / 0
   except ZeroDivisionError:
      print("Cannot divide by zero.")
   finally:
      print("This will always execute.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules are files containing Python code (functions, classes, variables). 
   Packages are directories containing multiple modules and an __init__.py file.
   import math

   # Using math module
   result = math.sqrt(16)
   print(result)  # Output: 4.0


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Reading from a file:
    with open("example.txt", "r") as file:
    content = file.read()
    print(content)

   Writing to a file:
   lines = ["Hello, World!", "This is a test."]

   with open("output.txt", "w") as file:
    for line in lines:
        file.write(line + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].