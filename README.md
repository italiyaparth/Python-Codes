# Index
 
- What is Python
- Install Python
- Python in Console
- 01. Python in VS Code
- Modules and pip in Python
- Python Inner Workings



# What is Python

    - Python is a dynamically typed, general purpose programming language that supports an object-oriented programming approach as well as a functional programming approach.
    - Python is an interpreted and a platform-independent open-source high-level programming language.
    - It is possible to integrate other programming languages within python.



# Install Python

    - visit www.python.org  >>>  select "Downloads" tab  >>>  select "Windows" or "macOS" or "Other Platforms"  >>>  click on "Python *version*" button and Install it.



# Python in Console

    - For Windows, open CMD and write "python --version"
    - For macOS, open ZSH and write "python3 --version"

    - Write "python" and press enter and repl(Read Evaluate Print Loop) will open in console and you can write "10+3", it will give "13"
    - To exit, write "exit()"



# 01. Python in VS Code

    - Make a file named "main.py", write some code in it
    - Open console, write "python main.py" and press enter, you will see the output of our code



# Modules and pip in Python

    - Python has two types modules: Built in & External
    
    - Built in  >>>  you can just write "import hashlib" in .py file
    - External  >>>  you have to install via console  >>>  In console, "pip install pandas" then "import pandas" in .py file



# Python Inner Workings

- Bytecode Generation:

    -- When you write Python code, it's initially in plain text form.
    -- Python compiles this source code into bytecode, which is a low-level representation of the code that the Python interpreter can understand and execute.
    -- Bytecode is platform-independent and stored in .pyc files (compiled Python files) or in memory if not saved to disk.

- Compilation vs. Interpretation:

    -- Python is often described as an interpreted language, but it actually goes through both compilation and interpretation.
    -- Compilation: Python source code is compiled into bytecode (.pyc) files by the Python interpreter when the module is first imported or executed.
    -- Interpretation: The bytecode is then executed by the Python interpreter.

- "__pycache__" Directory:

    -- When Python compiles source files into bytecode, it stores the resulting .pyc files in a special directory called __pycache__.
    -- This directory helps in caching compiled bytecode files, improving the performance of subsequent imports of the same modules.
    -- It's located alongside the Python source files and is typically automatically managed by Python.

- Bytecode Interpretation:

    -- Python bytecode is executed by the Python interpreter, which is implemented in C.
    -- The interpreter reads and executes each bytecode instruction one by one.
    -- During execution, the interpreter interacts with the Python runtime environment, which includes objects, modules, memory management, etc.

- Optimizations and Caching:

    -- Python implementations like CPython (the reference implementation) perform various optimizations to improve performance.
    -- These optimizations include bytecode caching (storing bytecode in memory or on disk), just-in-time (JIT) compilation, and other runtime optimizations.

- Execution Environment:

    -- Python code runs within a Python runtime environment, which provides access to standard libraries, modules, and other resources.
    -- The runtime environment manages memory, objects, exceptions, and other runtime aspects of Python execution.



# 