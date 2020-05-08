# PWN Roadmap #

## Prerequisites ##

Binary exploitation, or pwn, requires a familiarity with C and a scripting language (preferrably python).  

It is highly recommended you have completed 'Learn the Hard Stuff the Slow Way'.

## Progression of the PWN ##
The following sites are recommended for challenges that cover the subjects below:

* [Nightmare](https://github.com/guyinatuxedo/nightmare/tree/master/modules)

### Stack Based Buffer Overflows on x86 32 or 64 bit ###
This is a pwn staple.  The most important thing to do in these challenges is to understand how a program uses the stack as it executes.  The use of the stack structure is really what you are exploiting here.

### ROP Challenges ###
Return Oriented Programming is a natural result of NX Stacks.  If we can't execute on the stack then we have to direct execution somewhere else, hense ROP.  It is a step on the never ending chain of hackers working around the mitigations of defenders.  Again, understanding of the stack and how a program uses it is key here.

### Format String Challenges ###
An oldy, but a goody.  Wherever user input is passed into a function as a format string without significant sanitization, there is a format string vulnerability. And again, UNDSTANDING THE STACK IS KEY!  We are starting to see a pattern.

### Integer Overflows ###
This type of vulnerability bases its existence on the finite nature of certain primative types such as ints and longs.  Once these types reach their max values, if incrimented, they can turn negative or wrap around back to zero.  This can cause overflows, leaks, and general revelry.

### Heap Overflows ###
Heap overflows are similar to buffer overflows on the stack, but you are overflowing a different strucure, the heap.  This means we switch the drum beat from understanding the stack is key to UNDERSTANDING THE HEAP IS KEY!  Heap overflows come in many forms to include write-what-where's and function pointer overwrites.  Any data can be put on the heap, so exploit possibilities are only as finite as the program's use of the heap and your control over that use.

### Windows Exploitation ###

[Fu11Shade Windows Exploitation](https://fullpwnops.com/windows-exploitation-pathway.html)
