# Your First Application :tada:


## The Hello World

When learning to program for the first time, students are often instructed to write a program that outputs the string `Hello, World!`.

it’s a tradition among computer science teachers and professors to introduce the topic of programming with this example. As a result, `Hello, World!` is often the first program most people write.

It's no exception for us to not start with a simple `Hello, World`.. so let's do it.

### Using the python interactive shell

To write our first hello world programm in python, let's first do it from the terminal, using python interactive shell or REPL (Read-Eval-Print Loop).

The **REPL** allows you to run Python code interactively while working on a project or learning the language. This tool is available in every Python installation, so you can use it at any moment.

As a Python developer, you’ll spend a considerable part of your coding time in a REPL session because this tool allows you to test new ideas, explore and experiment with new tools and libraries, refactor and debug your code, and try out examples.


So let's get started :

- First Open you terminal emulator and type in python without any arguments :

```shell 
python
```

This command makes Python enter its interactive mode. The interpreter will run, and you’ll get an output that’ll look something like this:

```bash
Python 3.10.10 (main, Mar  5 2023, 22:26:53) [GCC 12.2.1 20230201] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```



The first line of this output shows information about your current Python version and the platform on which you’re running the interpreter. The second line shows a message with commands that you can run to get additional information about Python in general.

The last line, which is highlighted in the output, shows the primary prompt of a standard Python interactive session or shell. By default, this prompt consists of three greater-than signs (>>>), also known as chevrons. Its purpose is to communicate that the interpreter is ready to accept input.


The next step is to type `print("Hello, World!")` and hit enter :


like so :
```bash 
Python 3.10.10 (main, Mar  5 2023, 22:26:53) [GCC 12.2.1 20230201] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello, World!")
```

You’ll get an output that’ll look something like this:

```bash 
Python 3.10.10 (main, Mar  5 2023, 22:26:53) [GCC 12.2.1 20230201] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello, World!")
Hello, World!
>>> 
```
**Congratulations** you really did it.

### Using Visual Studio Code

using the command prompt do the following:

- Create a directory where we will be writing our first python program, Open your teminal and type the following commands:  
```bash
mkdir hello-world
```
- Change the directory to the newly created hello-world dir :
```bash
cd hello-world
```
- Open vscode inside this directory :
```bash
code .
```
A new instance of vscode will open, next click on the blue button .. "Yes, i trust the authors"


Next create a new file by clicking on `File > New File` or ++alt+ctrl+n++, a new prompt will open and you will need to select `Python File` option, this will create an untitled python file.

Next hit ++ctrl+s++ to save this file, save it as main.py

Now in **main.py** file type the following :
```python
print("Hello, World!")
```

Hit ++ctrl+s++ once again to save its content.

Finally do a right click inside **main.py** a menu will appear, choose the first option where it says `Run Code`. it will open a terminal at the bottom where it will run the main.py file .. if everything is fine you will see `Hello, World!` printed to the screen. 

**Congratulations** you really did it and wrote your first hello world programm.

## About the `#!python print()` function
 
In Python, `#!python print()` is a **built-in** function that is used to display output on the console. The `#!python print()` function takes one or more `arguments` and prints them to the console as a single string. 

Here's the general syntax of the `#!print()` function:

```python
print(value(s), ..., sep=' ', end='\n', file=sys.stdout, flush=False)
```


- **value(s)** is one or more values or expressions to be printed. These can be strings, variables, or other objects.

- **sep** is an optional parameter that specifies the separator to use between the values. By default, sep=' ' (a space) is used.

- **end** is an optional parameter that specifies the string to print at the end of the output. By default, end='\n' (a newline) is used.

- **file** is an optional parameter that specifies the output stream to which the output will be printed. By default, file=sys.stdout (the console) is used.

- **flush** is an optional parameter that specifies whether the output buffer should be flushed after printing. By default, flush=False (the buffer is not flushed).

In a next lesson we will experiment with all these arguments :wink:.