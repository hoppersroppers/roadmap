## Learn Networking Roadmap

Networking is hands down the most important thing to understand in security, and still, people just kind of fumble through it. Give yourself the hands on, practical knowledge required so that you can succeed. 

I would tell you to do the Ropper's Networking Course, except it isn't finished yet, so you should do this instead.

This pseudo-course is built in the style of Roppers, and has our characteristic lack of polish. When you have questions, ask in Slack!

Watch this [fun intro video](https://www.youtube.com/watch?v=3QhU9jd03a0&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo&index=29). I really like this series. It's all pretty good. Don't get distracted. 

Once you are done with that video, watch the CyberAces Networking videos and do whatever demos they tell you to do. Take time to pause the video anytime you don't understand something, and when they introduce commands, play around with them for a while. These videos might be 12 minutes long, but should take you at least 30 minutes. [CyberAces Networking](https://tutorials.cyberaces.org/tutorials.html) You only should watch Section 2: Networking. My Linux stuff is better than their Section 1 so you can skip that. 

Once you have worked through all those videos, move on to reading and doing. 

First go to [this section of my networking course](https://academy.hoppersroppers.org/course/view.php?id=20#section-3) and learn how to be good at Networking.  This mostly comes down to reading the RFCs (you'll learn to love them), opening up the actual packets in Wireshark, and understanding that there is nothing magic in Networking. Everything does exactly what it is supposed to do, it is just very hard to get an intuitive understanding without looking at the packets. 

Next, do [these network forensics walkthroughs from the CTF course](https://academy.hoppersroppers.org/course/view.php?id=7#section-6) to learn how to use Wireshark to troubleshoot and visualize what is actually going on. Remember, Wireshark is ground truth, and for everything you do throughout the rest of this course, you should do it on your local computer and look at it in Wireshark.

Then, because I haven't made the rest of the course yet, back to external resources!!!!  

This Digital Ocean guide is probably the best single short resource on the topic. Read it, when you don't understand something, google it, read other resources until it makes sense, then start again from the top. <https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols>

This Commotion resource is pretty good, once you finish Digital Ocean read this in the same way, taking your time. As you do things, check them out in Wireshark and learn how to do them.  <https://commotionwireless.net/docs/cck/networking/learn-networking-basics/>

I'll make the actual course in the next few months, but for now, this is probably the best way to actually learn it. 

Finally, this resource is way way more complicated. Read this: Specifically, 1.1-1.4, 1.9, <https://intronetworks.cs.luc.edu/current/html/intro.html>

Again, take your time to understand, and ask questions when you find them. 

Once you have finished all these things, start playing around with building your own Networking things. Do all the [things in here](https://academy.hoppersroppers.org/mod/assign/view.php?id=971) on localhost and see what happens. 

Check out Python sockets (this is a decent guide: https://realpython.com/python-sockets/) 

Check out Python webservers and hosting files on localhost. 

Learn all the basic Linux networking commands, ensuring we are still looking at everything in Wireshark: <https://itsfoss.com/basic-linux-networking-commands/>

Then you can probably learn everything else as you go, as long as you trust Wireshark, your resources, and physics, in that order. 

## Follow-On Resources:

My favorite resource to actually understand sockets is <https://beej.us/guide/bgnet/>. 

If you want to do some CTF challenges, check out these bad boys and girls.

<https://academy.hoppersroppers.org/mod/page/view.php?id=2054>








