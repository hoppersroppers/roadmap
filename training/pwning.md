# How to Learn Binary Exploitation Roadmap 

Course: [Nightmare: Roppers Remix](https://github.com/hoppersroppers/nightmare)

### "The best time to learn binex was five years ago. The second best time is now"

Trying to learn Pwn and Binary Exploitation but can't get over the initial hurdles? This is the Roppers path to learn how to write binary exploits and become a wizard. 

Binary exploitation, aka binex, is considered by many to be the among the most advanced and most interesting topic there is in security. Hacking is about making the cursed sand dance, and there's something special about making someone else's sand do what you want.

To me, binex is the peak of security knowledge but I'm biased because I get to pop shells and teach people how to pop shells for a living. 

## Prerequisites ##

Binary exploitation, or pwn, requires a familiarity with C and a scripting language (preferrably python). 

You can get away with not being great at C, but it's a limiting factor. If you wind up falling in love with pwn, you will learn C in pursuit of more shells. Don't worry about pre-requisites too much, just figure out what you can get done with your existing knowledge as you go, this course is very forgiving. 

## Progression of the PWN ##

Nightmare is an awesome Intro to Binary Exploitation / Reverse Engineering course [written by GuyInATuxedo](https://github.com/guyinatuxedo/nightmare) based around Capture the Flag challenges. I remixed and added a bit more of a focus on theory, hammering critical concepts, and slowly building expertise in alignment with the Roppers philosophy. 

* [Nightmare: Roppers Remix](https://github.com/hoppersroppers/nightmare)

All credit goes to GuyInATuxedo, I made this remix because I spend a lot of time teaching people Binary Exploitation and while I tell everyone the original Nightmare is the best course, I found myself supplementing the material with external links. This is my attempt to make a unified repo that has everything needed for a beginner to do a fully self-taught journey towards binary exploitation expertise.

#### Course Outline

1. [Foundational C](https://github.com/hoppersroppers/nightmare/modules/00-intro/readme.md)
2. [Intro to Assembly](https://github.com/hoppersroppers/nightmare/modules/01-intro_assembly/readme.md)
3. [Intro to Tooling](https://github.com/hoppersroppers/nightmare/modules/02-intro_tooling/readme.md)
4. [Beginner RE](https://github.com/hoppersroppers/nightmare/modules/03-beginner_re/readme.md)
5. [Overflows](https://github.com/hoppersroppers/nightmare/modules/04-Overflows/readme.md)
6. [Critical Misc.](https://github.com/hoppersroppers/nightmare/modules/05-CriticalMisc/readme.md)

## Overview

Being good at binex is a career long adventure, not just because of how quickly the human brain forgets this kind of abstract dark magic but because hackers constantly are adding new techniques to defend against exploitation... and other hackers are finding ways to bypass those defenses. The diagram below from this excellent presentation on [why memory safety will always be a concern](https://docs.google.com/presentation/d/1EscMOcMNOwi-bCgOthjiwIXE30w_SeHk3ahjyY0pX10/edit#slide=id.g72177b938a_1_18514) shows mitigations on the bottom and bypasses to those mitigations on the top, to give you an idea of the back and forth.

![Progression of the Pwn](https://pbs.twimg.com/media/FOE9minXIAAT9f7?format=jpg&name=large)

You won't learn all of the techniques in that diagram in the following course that attempts to teach binex, but it will get you up through about 2008's state of the art and you'll know enough to be able to teach yourself the follow on material. Plus, plenty of code written to 2008 standards is out there on the internet so you won't be lacking practical application. 

Welcome to the show!

## Discord 
If you get stuck on something for hours on end and google can't answer your question, try asking in the Nightmare discord (or if you just feel like talking about cool security things). Here is a link to it <https://discord.gg/p5E3VZF>. Again, Roppers doesn't have anything to do with this Discord, it's just a great place to learn. 

Also if you notice any typos or mistakes, feel free to mention it in the Discord. With how much content is here, there is bound to be at least a few.

### Recommended Linux/ARM Exploitation Resources ###

There are 1000 resources for this, but we aren't going to list them all. These are the best ones.

* <http://security.cs.rpi.edu/courses/binexp-spring2015/>
* <https://github.com/RPISEC/MBE>
* <https://samsclass.info/127/127_F19.shtml>
* <https://azeria-labs.com/writing-arm-shellcode/>

### Recommended Windows Exploitation Resources ###

There are 1000 resources for this. These are the best ones.

* [Fu11Shade Windows Exploitation](https://fullpwnops.com/windows-exploitation-pathway.html)
* <https://github.com/r3p3r/nixawk-awesome-windows-exploitation>


If you are looking for how to learn heap exploitation, [checkout this page](/heap.md).
