# How to Learn C Roadmap

Teaching yourself C is difficult, but it is doable. All things considered, I recommend you take a formal course on this if you are able to. If not, teaching yourself is very doable, but I consistently watch people struggle to stay motivated when learning by themselves.

First, why learn C? Fundamentally the reason is that C is as close to assembly as we want to get, so understanding c-isms is critical. Roppers is a site that guides students on their path to becoming reverse engineers and vulnerability researchers, and really understanding C is a core part of that journey. Check out this article [to learn about why you should learn C to learn how the computer works](https://steveklabnik.com/writing/should-you-learn-c-to-learn-how-the-computer-works). 

## The Curriculum

I don't have any real problems with [CS50](https://pll.harvard.edu/course/cs50-introduction-computer-science?delta=0), but the pacing is a bit slow. However, if you're someone who does better with course structure CS50 is the best way to go.

To start learning C, get a copy of the legendary K&R aka [The C Programming Language](https://en.wikipedia.org/wiki/The_C_Programming_Language). This is a somewhat controversial call, it's an old book, bit outdated, and recommending it is kind of agreed to be a boomer move. My thought process is 
I want people to learn from it as their textbook because it's my way of reminding everyone that what we do hasn't changed much in the last 50 years, and it provides common ground with the people who came before. Matters to me, might not to others. K&R is a bit intimidating, so honestly, I love <https://www.tutorialspoint.com/cprogramming/index.htm> as well. TutorialsPoint is not perfect, but it really gets the job done as a short reference guide. The combination of the two, plus man pages, plus a small amount of Google, is all you need.

Begin working through K&R, sometimes writing the code yourself but mostly using [example code from this solutions guide](https://clc-wiki.net/wiki/K&R2_solutions). K&R, and learning C overall, is more about reading code than writing code. Learning how good C code is written and exposing yourself to thousands of patterns is the best way to learn how C works, and then be able to build the mental models to write it properly yourself.

In parallel with K&R, do the [h0mbre C Course](https://github.com/h0mbre/Learning-C). Work through as much of h0mbre's material as you can until you get stuck, and then look up the correct chapter in K&R and work through using K&R as your reference. Bouncing between the two is a good way to keep material interesting and relevant. 

Keep doing this until you have finished most of of the assignments in the h0mbre course. 

This will take a while, but it winds up being a very balanced amount of work.

Don't worry about learning advanced data structures or algorithms beyond what is in h0mbre's assignments. Data structures and algorithms are for computer scientists, not hackers.

Once you are done with this curriculum, you will be ready for more advanced material along this path like [reverse engineering](hardstuff.md) and [binary exploits](pwning.md).

## Projects

You also can check out some of these projects to get a better understanding of some low level material and how things are implemented in the kernel of your operating system:
* <https://brennan.io/2015/01/16/write-a-shell-in-c/>
* <https://danluu.com/malloc-tutorial/>
* <https://beej.us/guide/bgnet/>
* <https://github.com/jamesroutley/write-a-hash-table>
* <https://blog.lizzie.io/linux-containers-in-500-loc.html>
* <http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/>
* <https://cstack.github.io/db_tutorial/>

If you are interested in getting a more complete Computer Science education, you work through the [Open Source Society University curriculum](https://github.com/ossu/computer-science/blob/master/README.md). It is excellent. I don't really like Computer Science, I think it doesn't apply that much to results-oriented hacking, but that is my own bias.

Overall, getting good at C involves writing a ton of code, reading a ton of code, and generally exposing yourself to challenging projects on a regular basis. Turns out, that is also how you learn [Binary Exploitation](pwning.md).
