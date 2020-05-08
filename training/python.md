# Python Basics

Message @Dennis Devey to tell him you are starting the course, and then use the #python chatroom for any questions or discussions.

# Codeacademy Python

This is going to take a while, but Codeacademy Python is the best way I've found to learn a first programming language. It is all done in an online editor and will let you progress with the appropriate hints. 

**NOTE: If you already know a programming language and don't need to re-learn what a tuple is, or are already learning Python using a different site or course, let us know. We can customize your experience here, there is no hard rule you have to use Code Academy.**

Keep us updated in chat on your progress, we will be reaching out to you too. When you are done, submit a screenshot of your completion certificate!!

   * Complete Code Academy Python
      * <https://www.codecademy.com/learn/python>

So you know a language now, right? Congratulations! The thing to remember is that all skills, if not used, will slowly atrophy. My recommendation is to constantly challenge yourself to maintain your skill level so when you have to write a program, you can whip something up immediately without having to relearn the syntax... or you can just ignore it completely and when the need arises, spend a half hour fumbling until you remember enough to get it working. Both of those are completely valid ways to maintain proficiency in a language. This course won't teach you any more languages, but if you continue in this pipeline you will learn C and some low level assembly.

 You are a big bad programmer now, but it has all been done in your browser! Time to learn how to do it from the terminal on your computer(s). This might require some googling..... don't worry, that is literally how programming works. You find something you need to do, and google how to do it. Then you forget how to do it, and you go and google it again the next time you do it. The next bit will help you set up your python environment in your OS's. Setting up environments is very time consuming, no matter what it is, but you will have to do this for basically every language, and every version of each language, so you will have to get good at it.

# Python in the Terminal

## Windows 

* <https://docs.python.org/3.3/using/windows.html>
1. What is a path? You might have to google around to understand it. Hint: If you mess this up, things get interesting.
2. Submit a screenshot of you running a .py file from the command line in Windows!

## Linux
* <https://docs.python.org/3.3/using/unix.html>
1. Submit a screenshot of you running a .py file from the command line in Linux!

* Know how to a run bash command from within a python script
   * ref: <https://stackoverflow.com/questions/26236126/how-to-run-bash-command-inside-python-script>
1. Submit a screenshot of you running a bash command from inside a python script.

Programming and scripting are different, but share most of the same principles, and these principles will be shared between all languages. Once you can program well in one language, you can learn any language, it just will take a bit to learn.

# Automate the Boring Stuff

Learn how to do practical work with Python using a book that walks you through a variety of basic projects. It is an important note that the book is all for Python 2, which has been deprecated. We recommend that you use Python 3. There are very minor differences throughout, but it does not detract from the educational experience.

Work through the chapters of this book, <https://automatetheboringstuff.com/>. The full course is in process. 

<ul>
			<li><a href="https://automatetheboringstuff.com//2e/chapter0/">Chapter  0 – Introduction</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter1/">Chapter  1 – Python Basics</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter2/">Chapter  2 – Flow Control</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter3/">Chapter  3 – Functions</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter4/">Chapter  4 – Lists</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter5/">Chapter  5 – Dictionaries and Structuring Data</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter6/">Chapter  6 – Manipulating Strings</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter7/">Chapter  7 – Pattern Matching with Regular Expressions</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter8/">Chapter  8 – Input Validation</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter9/">Chapter  9 – Reading and Writing Files</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter10/">Chapter 10 – Organizing Files</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter11/">Chapter 11 – Debugging</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter12/">Chapter 12 – Web Scraping</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter13/">Chapter 13 – Working with Excel Spreadsheets</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter14/">Chapter 14 – Working with Google Spreadsheets</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter15/">Chapter 15 – Working with PDF and Word Documents</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter16/">Chapter 16 – Working with CSV Files and JSON Data</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter17/">Chapter 17 – Keeping Time, Scheduling Tasks, and Launching Programs</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter18/">Chapter 18 – Sending Email and Text Messages</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter19/">Chapter 19 – Manipulating Images</a></li>
			<li><a href="https://automatetheboringstuff.com//2e/chapter20/">Chapter 20 – Controlling the Keyboard and Mouse with GUI Automation</a></li>
			<li><a href="/2e/appendixa/">Appendix A – Installing Third-Party Modules</a></li>
			<li><a href="/2e/appendixb/">Appendix B – Running Programs</a></li>
			<li><a href="/2e/appendixc/">Appendix C – Answers to the Practice Questions</a></li>
			</ul>


# Pwn Tools

## Introduction

[`Pwntools`](https://pwntools.com) is a grab-bag of tools to make exploitation during CTFs as painless as possible, and to make exploits as easy to read as possible.

There are bits of code everyone has written a million times, and everyone has their own way of doing it.  Pwntools aims to provide all of these in a semi-standard way, so that you can stop copy-pasting the same `struct.unpack('>I', x)` code around and instead use more slightly more legible wrappers like `pack` or `p32` or even `p64(..., endian='big', sign=True)`.

Aside from convenience wrappers around mundane functionality, it also provides a very rich set of `tubes` which wrap all of the IO that you'll ever perform in a single, unifying interface.  Switching from a local exploit to a remote exploit, or local exploit over SSH becomes a one-line change.

Last but not least, it also includes a wide array of exploitation assistance tools for intermediate-to-advanced use cases.  These include remote symbol resolution given a memory disclosure primitive (`MemLeak` and `DynELF`), ELF parsing and patching (`ELF`), and ROP gadget discovery and call-chain building (`ROP`).

We won't be getting into the exploitation assistance tools in this part of the course, but they'll come back again later.

## Tutorials

- [Installing Pwntools](https://github.com/Gallopsled/pwntools-tutorial/blob/master/installing.md)
- [Tubes](https://github.com/Gallopsled/pwntools-tutorial/blob/master/tubes.md)
    + Basic Tubes
    + Interactive Shells
    + Processes
    + Networking
    + Secure Shell
    + Serial Ports
- [Utility](https://github.com/Gallopsled/pwntools-tutorial/blob/master/utility.md)
    + Encoding and Hashing
    + Packing / unpacking integers
    + Pattern generation
    + Safe evaluation
- [Context](https://github.com/Gallopsled/pwntools-tutorial/blob/master/context.md)
    + Architecture
    + Endianness
    + Log verbosity
    + Timeout
    
## Final Challenge

Using Pwntools, write a python script to solve the first 5 challenges in Over the Wire Bandit. <https://overthewire.org/wargames/bandit/>

(Hint: <https://github.com/Gallopsled/pwntools-write-ups/blob/master/wargames/overthewire-vortex/level0/win.py> )


Once you have done everything in this section you should be overwhelmingly confident in your ability to write Python scripts to do just about anything you come across. 
    
