# How to Learn Binary Exploitation Roadmap 

Courses: [pwn.college](https://pwn.college/) and [Nightmare: Roppers Remix](https://github.com/hoppersroppers/nightmare)

### "The best time to learn binex was five years ago. The second best time is now"

Trying to learn Pwn and Binary Exploitation but can't get over the initial hurdles? This is the Roppers path to learn how to write binary exploits and become a wizard. 

Binary exploitation, aka binex, is considered by many to be among the most advanced and most interesting topics there is in security. Hacking is about making the cursed sand dance, and there's something special about making someone else's sand do what you want.

To me, binex is the best part of hacking, but I'm biased because I get to pop shells and teach people how to pop shells for a living. Roppers is basically my attempt at teaching the mentality and skills needed to be a great reverse engineer and vulnerability researcher, so you're in the right place.

## Prerequisites ##

To actually do binary exploitation, or pwn, requires [a familiarity with C](/training/c.md) and a scripting language, preferably Python. 

You can get away with not being great at C, but it's a limiting factor. If you wind up falling in love with pwn, you will learn C in pursuit of more shells. Don't worry about prerequisites too much, just figure out what you can get done with your existing knowledge as you go, this course is very forgiving. 

## Progression of the PWN ##

I highly recommend you start with the material available at [pwn.college](https://pwn.college/). It is a free site run by some awesome people from Arizona State University and it does the best job of providing great video curriculum, a range of challenges, and an easy environment to get started. Following pwn.college's material will definitely get you through most of the basics, but you need to work through a ton of challenges to really make things stick. In order to do that, I recommend you work through Nightmare challenges once you've learned a subject from pwn.college in order to reinforce all the lessons.

Nightmare is an awesome Intro to Binary Exploitation / Reverse Engineering course [written by GuyInATuxedo](https://github.com/guyinatuxedo/nightmare) based around Capture the Flag challenges. I remixed and added a bit more of a focus on theory, hammering critical concepts, and slowly building expertise in alignment with the Roppers philosophy. [Nightmare: Roppers Remix](https://github.com/hoppersroppers/nightmare)

All credit goes to GuyInATuxedo, I made this remix because I spend a lot of time teaching people Binary Exploitation and while I tell everyone the original Nightmare is the best course, I found myself supplementing the material with external links. This is my attempt to make a unified repo that has everything needed for a beginner to do a fully self-taught journey towards binary exploitation expertise.

Together, pwn.college and Nightmare work well together to teach all the basics you need to know and the differences in approaches means that there is something that will stick with everyone. Binex is about learning how to grind just as much as it is about learning the techniques, so you need a little of everything.

#### Course Outline

* [pwn.college CSE365 Videos](https://www.youtube.com/playlist?list=PL-ymxv0nOtqqW1sDfN6UGUfJTcYqYH9CM)
* [pwn.college CSE365 Dojo](https://pwn.college/cse365-s2023/)

1. [Foundational C](https://github.com/hoppersroppers/nightmare/blob/master/modules/00-intro/readme.md)
2. [Intro to Assembly](https://github.com/hoppersroppers/nightmare/blob/master/modules/01-intro_assembly/readme.md)
3. [Intro to Tooling](https://github.com/hoppersroppers/nightmare/blob/master/modules/02-intro_tooling/readme.md)
4. [Beginner RE](https://github.com/hoppersroppers/nightmare/blob/master/modules/03-beginner_re/readme.md)
5. [Overflows](https://github.com/hoppersroppers/nightmare/blob/master/modules/04-Overflows/readme.md)
6. [Critical Misc.](https://github.com/hoppersroppers/nightmare/blob/master/modules/05-CriticalMisc/readme.md)

* [pwn.college CSE365 Videos](https://www.youtube.com/playlist?list=PL-ymxv0nOtqqQzEncNuE6jetlJAiBUda-)
* [pwn.college CSE466 Dojo](https://pwn.college/cse466-f2023/)

Then do the rest of Nightmare. 

## Overview

Being good at binex is a career long adventure, not just because of how quickly the human brain forgets this kind of abstract dark magic but because hackers constantly are adding new techniques to defend against exploitation... and other hackers are finding ways to bypass those defenses. The diagram below from this excellent presentation on [why memory safety will always be a concern](https://docs.google.com/presentation/d/1EscMOcMNOwi-bCgOthjiwIXE30w_SeHk3ahjyY0pX10/edit#slide=id.g72177b938a_1_18514) shows mitigations on the bottom and bypasses to those mitigations on the top, to give you an idea of the back and forth.

![Progression of the Pwn](https://pbs.twimg.com/media/FOE9minXIAAT9f7?format=jpg&name=large)

You won't learn all of the techniques in that diagram in the following course that attempts to teach binex, but it will get you up through about 2008's state of the art and you'll know enough to be able to teach yourself the follow on material. Plus, plenty of code written to 2008 standards is out there on the internet so you won't be lacking practical application. 

Welcome to the show!

## Discord 

If you get stuck in pwn.college, check out [their Discord](https://discord.gg/pwncollege)

If you get stuck on something in Nightmare for hours on end and google can't answer your question, try asking in the Nightmare discord (or if you just feel like talking about cool security things). Here is a link to it <https://discord.gg/p5E3VZF>. Again, Roppers doesn't have anything to do with these Discords, they're just great places to learn. 

Also if you notice any typos or mistakes, feel free to mention it in the Discord. With how much content is here, there is bound to be at least a few.

### Recommended Linux/ARM Exploitation Resources ###

There are 1000 resources for this, but we aren't going to list them all. These are the best ones.

* <http://security.cs.rpi.edu/courses/binexp-spring2015/>
* <https://github.com/RPISEC/MBE>
* <https://samsclass.info/127/127_F19.shtml>
* <https://azeria-labs.com/writing-arm-shellcode/>

### Recommended Windows Exploitation Resources ###

There are 1000 resources for this. These are the best ones.

* [Corelan Exploit Blog Posts](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
   * If you have money, pay for the Corelan courses. As good as it gets.
* [Nixawk Windows Awesome List](https://github.com/r3p3r/nixawk-awesome-windows-exploitation)
* [Fu11Shade Windows Exploitation Awesome List](https://fullpwnops.com/windows-exploitation-pathway.html)
* [Windows Extreme Vulnerable Driver](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver)


If you are looking for how to learn heap exploitation, [checkout this page](/heap.md).
If you are looking for how to learn firmware reverse engineering, [checkout this page](/firmware.md)
