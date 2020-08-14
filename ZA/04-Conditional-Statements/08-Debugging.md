# Debugging

[slide]
# Video

[vimeo-video startTimeInSeconds="4025" endTimeInSeconds="4222"]
[stream language="EN" videoId="341553633" default /]
[stream language="RO" videoId="387288483"  /]
[/vimeo-video]

[/slide]

[slide]
# Debugging
So far, we wrote a lot of code, and there were some mistakes in it, right? Now we will show a tool that can help us find mistakes more easily: **the debugger**.

# What is "Debugging"?
**Debugging** is the process of "**attaching**" to the program execution, which allows us to **track step by step the process**. 

We can track **line by line** what happens in our program, what path it follows, what are the values of defined variables at each step of debugging, and many other things that allow us to detect errors (**bugs**).

[image assetsSrc="debugging.png" /]

# Debugging in PyCharm
Pressing `[Shift + F9]` will start the program in debug mode

We can go to the next step with `[F8]`

We can create breakpoints using `[Ctrl + F8]`
  * We can go directly to them by using `[F9]`

[image assetsSrc="debug_pycharm.png" /]

[/slide]