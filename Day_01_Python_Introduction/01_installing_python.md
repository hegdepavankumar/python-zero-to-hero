# Installing Python

If you want to learn to program with Python using this tutorial, you need to try out the code examples. You can use a website like [repl.it](https://replit.com/languages/python3), but I highly recommend installing Python. That way you don't need to open a web browser just to write code, and you can work without an Internet connection.

It doesn't matter which operating system you use because Python runs great on Windows, Mac OSX, Linux and many other operating systems. However, installing and launching Python are done differently on different operating systems, so just follow your operating system's instructions.

Let's get started!

## Windows

Installing Python on Windows is a lot like installing any other program. <br>
Step 1 : Go to the official Python website.[🔗](https://www.python.org/) <br>
Step 2 : Move your mouse over the blue Downloads button, but don't click it. Then click the button that downloads the latest version of Python. <br>
Step 3 : Run the installer.(Install as usual like any .exe windows applications). <br>
Step 4 : Make sure that the launcher gets installed. <br>

## Mac OS
Install Python 3 as a part of the Command Line Developer Tools
To check the current version of Python that is already installed, open the Terminal application by typing command + space and then spelling out terminal and hitting return. Now, type the following command, and then hit return to see that you have Python 2.7 pre-installed on your Mac:

% python --version
Python 2.7.18

Now, try the following command to check whether or not Python 3 is installed on your Mac:

~ % python3 --version

The following message will probably appear on the Terminal window,

xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.

And alongside the Terminal window, a dialog box will automatically appear that says this command requires the command line developer tools. First, let’s identify the command-line developer tools. To put it briefly, the command line developer tools package is a set of tools mostly used in the development process. They help run specific commands, such as make, git, python3, etc. So, although there are other ways to install Python 3.x on Mac without installing the command line developer tools, I recommend you install it because it provides a string of tools for development on Mac. To install the package, click on the Install button, and follow the steps to complete the installation process. Once the installation process is complete, rerun the previous command. Yes, Python 3.x is installed on your Mac.

~ % python3 --version
Python 3.8.9

![img 2](https://user-images.githubusercontent.com/85627085/232229759-0cd061ed-2494-44db-8cc6-de8b07937887.png)

~ % print(“Hello, World!”)

![img 3](https://user-images.githubusercontent.com/85627085/232230130-65835a69-f622-422c-9990-666ddf08f846.png)

## Linux

Installing Python 3 on Linux
Download and Install Python:
Before starting with the installation process, you need to download it. For that all versions of Python for Linux are available on [python.org](https://www.python.org/).

![python-version-download](https://user-images.githubusercontent.com/85627085/232230320-dba93a92-36f2-4d93-9b5f-2da6fdb7b633.jpg)

Download the required version and follow the further instructions for the installation process. <br>
Beginning the installation. <br>
For almost every Linux system, the following command could be used to install Python directly: <br>

```
$ sudo apt-get install python3.8
```
To verify the installation enter the following commands in your Terminal.
```
python3.8
```

Let’s consider a simple Hello World Program.
```
# Python program to print
# Hello World
  
print("Hello World")
```

## Running Python on Windows 
( In this tutorial I am using Windows OS )
1. Open a PowerShell from your start menu or start screen. <br>
2. Type py and press Enter. You should see something like this:

![img 1](https://user-images.githubusercontent.com/85627085/232227452-54f0d7eb-b915-4b00-89ce-a8345da50db0.png)

3. Now you can type exit() and press Enter to get out of Python. Or you can just close the PowerShell or Terminal window. <br>

## Summary

Now you should have Python installed, and you should be able run it. <br>

If you have trouble with this tutorial, please [tell me about it]() and I'll make this tutorial better, or [ask for help]() online. If you like this tutorial, please [give it a star]().

## Reference
1. [W3Schools](https://www.w3schools.com/)
2. [GeeksforGeeks](https://www.geeksforgeeks.org/)

You may use this tutorial freely at your own risk. See [LICENSE](https://github.com/hegdepavankumar/python-zero-to-hero/blob/main/LICENSE). <br>

| [Next](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/Day_01_Python_Introduction/02_what_is_python.md) | [List of contents](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/list_of_contents.md) |
