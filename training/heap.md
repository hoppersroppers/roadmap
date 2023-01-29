# How to Learn Heap Exploitation Roadmap 

If you already know binex, you know what's coming up next... heap exploitation. Learning how to heap is the same beast but a different animal. 

## Prerequisites ##

You should already be pretty good at binary exploitation. If not, check out [my page on how to learn binex](/pwning.md). 

## Progression of the (Heap) PWN ##

Learning heap is just like binex: put in the time and you'll be decent.

1. Make sure you [understand the heap data structure](https://www.codecademy.com/learn/complex-data-structures/modules/cspath-heaps). Feel free to rush through this.
2. Once again, we go back to Azeria's material, this time on [understanding the glibc heap](https://azeria-labs.com/heap-exploitation-part-1-understanding-the-glibc-heap-implementation/)
3. Extremely similar to the last one, we are going to read this on [glibc from Sploitfun](https://sploitfun.wordpress.com/2015/02/10/understanding-glibc-malloc/).

4. Then if you hate yourself, you should spend some time with the [actual source code of the glibc malloc](https://sources.debian.org/src/glibc/2.28-10/malloc/malloc.c/). You don't need to understand it/memorize anything, it's just a good idea to get eyes on for a little bit. A ton of heap work is reading the specific malloc implementation you are working with, especially if it's something custom.

5. Now that you almost understand things, [learn about freeing from Azeria](https://azeria-labs.com/heap-exploitation-part-2-glibc-heap-free-bins/).
6. And finally, after all this work learning the foundation, [this tutorial from Azeria on actual exploitation should almost make sense](https://azeria-labs.com/heap-exploit-development-part-1/).  
7. Then work through these similar heap exploit writeups from Sploitfun.
* <https://sploitfun.wordpress.com/2015/02/26/heap-overflow-using-unlink/>
* <https://sploitfun.wordpress.com/2015/03/04/heap-overflow-using-malloc-maleficarum/>
* <https://sploitfun.wordpress.com/2015/06/09/off-by-one-vulnerability-heap-based>
* <https://sploitfun.wordpress.com/2015/06/16/use-after-free/>

I hate to say this, but if you have money, you should spend it on [this course](https://www.udemy.com/course/linux-heap-exploitation-part-1/) from Max Kamper. It is truly excellent and is my recommended way to learn heap. Spend time on the assignments, pause the videos and actually do the work. Video courses by themselves never are that useful, but you reaaaallly can't learn heap by watching videos.

If you don't want to spend money, that is fine.The real work is starting and grinding through <https://github.com/shellphish/how2heap> and <https://guyinatuxedo.github.io/25-heap/index.html> in parallel. 

If you finish both of these you'll be ready for most heap challenges you see in CTFs, it will just take quite some time to get comfortable.
