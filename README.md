# The Comprehensive Python Guide

Welcome to the Comprehensive Python Guide! In this guide, I will explain the basics of Python,
and take you far beyond them. Here is what you will need:

- Python 3.7 or later installed
- Pip, Python's package manager, installed

If these aren't installed, read section 0. Otherwise, feel free to skip straight to section 1!

# 0:  Installing Python and Pip

## 0.1:  Installing Python and Pip on Windows

### 0.1.1 Installing from Python.org

In your favorite web browser, go to [the Python home page](https://python.org) and click the menu 
bar. You will see a section called "Downloads". Click on Windows under that section, and click 
"Latest Python 3 release". Scroll down to the files section, then download the Windows Installer
that says it is 64-bit. When it is downloaded, run the installer. Feel free to choose whatever 
options you want in the installer, but ensure that you install pip alongside Python. Congratulations,
you just installed Python!

### 0.1.2 Installing from Scoop

Scoop is a package manager for Windows. To install with scoop, simply open a terminal and type
`scoop install python`. Once it is installed, you're done. Congratulations, you just installed Python!

## 0.2 Installing Python and Pip on MacOs

### 0.2.1 Installing from Python.org

Follow the same steps as Windows, but instead choose one of the MacOs installers, depending on what 
CPU you have in your system. 

### 0.2.2 Installing with Brew

Brew is a package manager for MacOs. To install with Brew, open a terminal and type `brew install python3`. Congratulations, you just installed Python!

## 0.3 Installing on Linux

Python is installed by default on most ditributions. If you don't have it, use your system package manager to install it.

# 1 Hello World

In this section, I will explain how to write a simple "Hello, World!" program in Python.

## 1.1 Opening Python in your terminal

First, we need to open a terminal. On windows, press Win+R, and type "cmd". On MacOs, open the launchpad and click "Terminal". On Linux, open your favorite terminal emulator. Then in your terminal,
type `python3`. 

## 1.2 Programming the Hello World Program

After typing `python3`, you should see something like this: 
```
Python 3.9.5 (tags/v3.9.5:0a7dcbd, May  3 2021, 17:27:52) [MSC v.1928 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
If you do not see something like this, refer to Section 0. Now for the programming! When you see 
this, type `print("Hello, Python!")`. Then, press enter. You should see `Hello, Python!` printed to
the screen. Congratulations, you coded your first Python program!

## 1.3 How this works

Congratulations on programming your first program! But, it is important to understand how Python 
works. When programming, it is important to see what the computer is going to see. Let's break down
the program. First, you have `print`. The word `print` does not do anything on it's own, but when you 
add brackets, it turns into a **function call**. A function call executes code that has already been 
programmed, but `print()` on it's own does nothing. It needs something inside the brackets. This is 
where **literals** come in. Literals are types of data. In python, the built-in literals are strings,
numbers, floats, lists, tuples, dictionaries, and a few others. We just used a string literal. There 
are a few ways to use a string literal. You can use "double quotes", 'single quotes', """
triple double quotes to span multiple lines""", or '''triple single quotes for the same thing'''.
Literals are great, but what if we wanted to print "Hello, Python!" multiple times? Typing 
`print("Hello, Python!")` over and over again would be very inneficient. That is where **variables**
come into play.

# 2 Variables

Variables are one of the most important things to a programmer. It allows you to store a literal 
and use it multiple times, under a single name. We are going to rewrite our "Hello, Python!" program
to use a variable.

## 2.1 Programing "Hello, Python!" with variables

To assign a variable, we follow the following template:  `{variable-name} = {value}`. We are now
going to make a variable for the string "Hello, Python!". We are going to name this variable `text`.
In your terminal with Python running, type `text = "Hello, Python!"`. You will notice that nothing will
print to the screen. Now, we are going to use this variable. Type `print(text)`. You will see 
`Hello, Python!` printed to the screen.

## 2.2 How variables work

This program does the same thing as the first program, but differently. First, we set the variable.
Think of this as the master copy of the document. Then, we do `print(text)`. When we do this, we 
kind of take a copy of the master document for use. This improves our programs efficiency, but 
typing `print(text)` multiple times is very inneficient. Next, we are going to look at `loops`.

# 3 Loops