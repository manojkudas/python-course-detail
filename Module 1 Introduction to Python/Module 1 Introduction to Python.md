# 🛠 History & features of Python

1. Python was created by Guido van Rossum in 1989.
2. The first public release of Python came in 1991.
3. Python was designed to emphasize readability and simplicity.
4. Its name was inspired by "Monty Python’s Flying Circus".
5. Python supports multiple programming paradigms.
6. It is an interpreted programming language.
7. Python is open source and free to use.
8. Python supports object-oriented programming (OOP).
9. Python also supports procedural programming.
10. Functional programming concepts are supported as well.
11. Python has automatic memory management.
12. It provides dynamic typing for flexible coding.
13. Python includes a large standard library.
14. It has strong support for modules and packages.
15. Python is widely used in web development.
16. It is popular in data science and analytics.
17. Python plays a major role in AI and machine learning.
18. It is commonly used for automation and scripting.
19. Python runs on Windows, Linux, and macOS.
20. Python remains one of the most popular languages worldwide.


- Installing Python & IDE setup

	Here’s a clear, step‑by‑step guide you can include in your course repo for **Installing Python & IDE Setup**. This will help learners get started smoothly:

---

# 🛠 Installing Python & IDE Setup

## 1️⃣ Install Python

- Go to the official download page: [python.org/downloads](https://www.python.org/downloads/)
- Choose the latest **Python 3.x** version (avoid Python 2.x).
- During installation:- ✅ Check **“Add Python to PATH”** (important for running Python from the terminal).
- Keep default options, but ensure **“Install pip”** and **“tcl/tk and IDLE”** are selected.

### Verify Installation

Open a terminal/command prompt and run:

```bash
python --version
```

or

```bash
python3 --version
```

You should see something like:

```
Python 3.11.9
```

---

## 2️⃣ Install an IDE (Integrated Development Environment)

### Option A: **VS Code (Recommended)**

- Download from [code.visualstudio.com](https://code.visualstudio.com/)
- Install the **Python extension** (search “Python” in Extensions Marketplace).
- Configure interpreter:- Press `Ctrl+Shift+P` → type **Python: Select Interpreter** → choose your installed Python version.

### Option B: **PyCharm**

- Download from [jetbrains.com/pycharm](https://www.jetbrains.com/pycharm/)
- Community Edition is free.
- PyCharm auto‑detects Python installation.

### Option C: **Jupyter Notebook**

- Install via pip:		pip install notebook
- Run:		jupyter notebook
- Opens in your browser, great for data science & interactive coding.

---

## 3️⃣ Install Git (for GitHub Integration)

- Download from [git-scm.com](https://git-scm.com/)
- Verify installation:		git --version
- Configure GitHub:		git config --global user.name "Your Name"  
  git config --global user.email "your@email.com"

---

## 4️⃣ Test Your Setup

Create a file `hello.py`:

```python
print("Hello, Python World!")
```

Run it:

```bash
python hello.py
```

---

## 📌 Suggested Repo Structure for Setup Module

```
Module-0-Setup/                              
│── README.md        # Installation instructions                              
│── hello.py         # First Python script                              
│── IDE-guide.md     # IDE setup notes                              
│── screenshots/     # Optional images for learners
```

---

# 🛠 First program: Hello World

Here’s a simple **Python Hello World program** with a clear explanation you can use in your course repo:

---

## 🐍 Python Hello World Program

```python
# This is a comment in Python                  
# The following line prints text to the console                  
                  
print("Hello, World!")
```

---

## 🔎 Explanation

- **`# This is a comment`**  
  Anything after `#` is ignored by Python. Comments are used to explain code.
- **`print()` function**  
  This is a built‑in Python function that outputs text or values to the console.
- **`"Hello, World!"`**  
  The text inside quotes is called a **string**. Python will display it exactly as written.
- **Output:**  
  When you run the program, the console shows:

		Hello, World!

---

## 💡 Why "Hello, World!"?

- It’s the traditional first program in any language.
- Helps confirm that Python is installed correctly.
- Shows how to run a basic script and produce output.

---

## ▶️ How to Run

1. Save the file as `hello.py`.
2. Open a terminal/command prompt.
3. Navigate to the folder containing `hello.py`.
4. Run:		python hello.pyor (depending on your system):		python3 hello.py


---

# 🐍 Python Syntax, Variables, and Data Types

## 1️⃣ Python Syntax Basics

Python emphasizes **readability** and uses indentation instead of braces `{}`.

Example:

```python
# Correct indentation              
if True:              
print("This is indented correctly")
```

- **Indentation:** Default is 4 spaces (not tabs).
- **Case-sensitive:** `Variable` and `variable` are different.
- **Comments:** Use `#` for single-line comments, and triple quotes (`""" ... """`) for multi-line docstrings.

---

## 2️⃣ Variables

Variables are used to store data. In Python:

- No need to declare type explicitly.
- Assignment uses `=`.

Example:

```python
name = "Manoj"      # String              
age = 25            # Integer              
height = 5.9        # Float              
is_student = True   # Boolean
```

### Rules for Variables

- Must start with a letter or underscore (`_`).
- Cannot start with a number.
- No special characters (`@`, `$`, `%`).
- Case-sensitive.

---

## 3️⃣ Data Types

Python has several built-in data types:


| **Type** | **Example**                          | **Description**               |
|----------|--------------------------------------|-------------------------------|
| `int`    | `x = 10`                             | Whole numbers                 |
| `float`  | `y = 3.14`                           | Decimal numbers               |
| `str`    | `name = "Python"`                    | Text (string)                 |
| `bool`   | `flag = True`                        | Boolean values                |
| `list`   | `nums = [1,2,3]`                     | Ordered, mutable collection   |
| `tuple`  | `coords = (10,20)`                   | Ordered, immutable collection |
| `set`    | `unique = {1,2,3}`                   | Unordered, unique values      |
| `dict`   | `person = {"name":"Manoj","age":25}` | Key-value pairs               |


---

## 4️⃣ Type Checking & Conversion

Use `type()` to check a variable’s type:

```python
x = 10              
print(type(x))   # <class 'int'>
```

Convert between types:

```python
num = "100"              
print(int(num))   # 100 (string → int)              
print(float(num)) # 100.0 (string → float)
```

---

## 5️⃣ Example Program

```python
# Demonstrating variables and data types              

name = "Python"              
version = 3.11              
is_popular = True              
features = ["Easy", "Readable", "Powerful"]              

print("Language:", name)              
print("Version:", version)              
print("Popular:", is_popular)              
print("Features:", features)
```

**Output:**

```
Language: Python              
Version: 3.11              
Popular: True              
Features: ['Easy', 'Readable', 'Powerful']
```

---

 
