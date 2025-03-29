K-Sharp (K#) Programming Language

K-Sharp (K#) is a modern, high-performance, and developer-friendly programming language designed as an improved blend of C# and Python. It aims to simplify syntax, enhance productivity, and maintain the robust structure and object-oriented principles of C#.

K# introduces clean syntax, dynamic typing capabilities, and powerful libraries while preserving the familiarity of C#'s core features like classes, methods, and exception handling.


---

Features

Improved Syntax: Cleaner and shorter syntax inspired by Python.

Dynamic Typing Support: Combine dynamic and static typing effortlessly.

Enhanced Libraries: Built-in libraries for file handling, networking, GUI, and more.

Cross-Platform: Write once, run anywhere (Windows, MacOS, Linux).

Built-In REPL: Interactive mode for quick testing and debugging.

Integrated Memory Management: Automatic garbage collection and optimized performance.



---

Installation

To install K-Sharp, follow these steps:

Using Package Manager

# Install the K-Sharp CLI via the command line  
pip install ksharp-cli

Manual Installation

1. Download the latest release from the official K-Sharp GitHub repository.


2. Extract the contents and add ksharp to your system's PATH.


3. Run the following command to verify the installation:



ksharp --version


---

Usage

1. Running K# Files

To run a K-Sharp script:

ksharp myscript.ksh

2. Using the REPL (Interactive Mode)

To open the interactive shell, use:

ksharp

You can then execute commands like:

>>> print("Hello, World!")  
>>> var x = 10  
>>> print(x * 5)


---

Syntax Overview (K# Basics)

Hello World

print("Hello, World!")

Variables and Data Types

K# supports both static and dynamic typing:

# Dynamic typing  
x = 42  
message = "Welcome to K-Sharp"  

# Static typing (optional)  
var y: int = 100

Conditional Statements

x = 10  
if x > 5:  
    print("x is greater than 5")  
else:  
    print("x is less than or equal to 5")

Loops

# For loop  
for i in range(5):  
    print(i)  

# While loop  
counter = 0  
while counter < 5:  
    print(counter)  
    counter += 1

Functions

def greet(name):  
    print(f"Hello, {name}!")  

greet("Alex")

Classes and Objects

class Person:  
    def __init__(self, name, age):  
        self.name = name  
        self.age = age  

    def greet(self):  
        print(f"Hi, I'm {self.name} and I'm {self.age} years old.")  

p1 = Person("Sarah", 25)  
p1.greet()


---

Advanced Features

Lambda Functions

square = lambda x: x * x  
print(square(5))  # Output: 25

List Comprehensions

numbers = [x for x in range(10) if x % 2 == 0]  
print(numbers)  # Output: [0, 2, 4, 6, 8]

Built-in Libraries

K# comes with powerful libraries for various tasks:

os for file and directory operations

net for network programming

gui for creating graphical user interfaces


Example:

import os  

current_directory = os.getcwd()  
print(f"Current Directory: {current_directory}")


---

Contributing

We welcome contributions from the community! Whether it's bug fixes, new features, or documentation improvements, your help is appreciated. Please follow the contributing guidelines in the repository.


---

License

K-Sharp is licensed under the MIT License.

