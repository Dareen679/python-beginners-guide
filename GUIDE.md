
# Getting Started with Python: A Beginner's Guide

## 1. Introduction to Python

### What Is Python?
Python is a popular programming language that is known for being easy to read and learn. It allows people to write instructions that computers can follow to complete different tasks.

### Why Is Python Useful?
Python is used in many areas, including:
- Web development
- Data analysis
- Artificial intelligence and machine learning
- Automation of repetitive tasks
- Cybersecurity and IT administration

### Why Is Python Good for Beginners?
Python uses simple, readable syntax. Beginners can focus on understanding programming concepts without having to write complicated code.

### Your First Python Example

```python
print("Hello, World!")
```

When you run this program, Python displays:

```text
Hello, World!
```

The `print()` function displays information on the screen.

### Tips for Getting Started
1. Practice writing small programs regularly.
2. Read error messages to understand mistakes.
3. Start with simple examples before trying larger projects.
4. Experiment with code to see how it works.

### Beginner Practice Exercise

Try changing the message in the print() function.

For example:

```python
print("I am learning Python!")
```

Expected output:

```text
I am learning Python!
```

This exercise helps beginners understand how Python displays information using the print() function.


## 2. Setting Up Python

### Step 1: Install Python
1. Visit https://www.python.org/downloads/
2. Download the latest stable version of Python for your operating system.
3. Run the installer and follow the instructions.
4. On Windows, select the option to add Python to PATH if available.
5. Open Terminal or Command Prompt and check the installation:

```bash
python --version
```

On macOS or Linux, you may need to use `python3 --version`.

### Step 2: Install Visual Studio Code
1. Visit https://code.visualstudio.com/
2. Download and install Visual Studio Code.
3. Open VS Code.
4. Go to Extensions and install the Python extension by Microsoft.

### Step 3: Write Your First Program
1. Create a file named `hello.py`.
2. Type the following code:

```python
print("Hello, Python!")
```

3. Save the file.
4. Open the terminal in VS Code.
5. Run the program:

```bash
python hello.py
```

On macOS or Linux, use `python3 hello.py` if needed.

Expected output:

```text
Hello, Python!
```

You have now created and run your first Python program!


## 3. Python Basics

### Variables and Data Types

Variables are used to store information in a Python program.

```python
name = "Alex"
age = 20
height = 5.8
is_student = True

print(name)
print(age)
```

Common Python data types include:

- String (`str`): Text, such as `"Alex"`
- Integer (`int`): Whole numbers, such as `20`
- Float (`float`): Decimal numbers, such as `5.8`
- Boolean (`bool`): `True` or `False`

### Conditional Statements

Conditional statements allow a program to make decisions.

```python
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are under 18.")
```

The program checks whether the condition is true and runs the matching block of code.

### Loops

Loops allow us to repeat instructions without writing the same code multiple times.

Example of a for loop:

```python
for number in range(1, 4):
    print(number)
```

Expected output:

```text
1
2
3
```

Example of a while loop:

```python
count = 1

while count <= 3:
    print(count)
    count += 1
```

Both loops print the numbers 1, 2, and 3.

### Practice Exercise

Create a variable named `favorite_language` and print its value.

```python
favorite_language = "Python"
print("My favorite language is", favorite_language)
```

Expected output:

```text
My favorite language is Python
```

## Conclusion

Python is a useful programming language for beginners. By learning variables, conditions, and loops, students can begin creating their own programs. Practicing these concepts regularly helps build confidence and programming skills.
