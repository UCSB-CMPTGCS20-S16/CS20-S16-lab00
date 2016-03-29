# CS20-S15-lab00
CMPTGCS-20-S15-lab00 Hello World in Python 2.7


For this lab, there is one goal: write a Python 2.7 program that prints the string `Hello, World!` as its output.

In this sense, we are following a long tradition: for [more than 40 years](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) it has been a tradition to make printing `Hello, World!` be the first thing you do when learning a new programming language.

In Python, this program is very short.  It looks like this:

```Python
print 'Hello, World!'
```

That's it!   Now, you can also add, on the first line, a *comment* with your name, and information about the course, for example:

```Python
# Chris Gaucho, for CMPTGCS 20, S16
print 'Hello, World!'
```

You are encouraged to do that, because it helps someone looking at your code know that *you* wrote it.  But, other than that, it isn't necessary.  In general, in computer programming, a *comment* is something that is intended only for human readers of the code, and is otherwise "ignored by the system".   Nearly every programming language has some way to express comments, though the exact rules for formatting of comments--that is, the *syntax* of comments--differs from one language to another.

In Python, a `#` starts a comment.  Everything from the `#` to the end of that line is part of the comment.

Now, how will you create this bit of code?  Assuming you have a laptop in front of you, the best way is to use a piece of software called IDLE, which is part of the download for Python 2.7.11.  Let's explore that option first.

# Downloading Python 2.7.11 (including IDLE) for your system.

These instructions assume <b>you are working with a Windows or Mac system.</b>  

* <b>If you are running Linux</b>, it is assumed that you already have some system administration skills (otherwise, you'd be running Windows or Mac.   In particular, we assume you know how to install software for your distribution of Linux with an appropriate package manager, e.g. apt-get, yum, dpkg, etc.    If you are on Linux, install Python 2.7.11 in whatever way is appropriate for your distribution of Linux.  That's all the help we can provide.

For Windows or Mac, you can install Python 2.7.11 by visiting: http://python.org and clicking the Downloads link.

* BE SURE YOU GET PYTHON 2.7.11 (or a later version on the 2.7 branch.)  
* FOR THIS COURSE, YOU DO NOT WANT ANY VERSION OF PYTHON STARTING WITH 3.

If you already have a version of Python 3 on your system, that's ok.  

Supposedly, Python 2 and Python 3 can happily co-exist.   What's this all about?  We'll explain in lecture, but if you missed the lecture, or want to learn more, here's some information: https://wiki.python.org/moin/Python2orPython3

As for why we are using Python 2 rather than 3 in this course, the answer is:
* The [textbook we are using (Guttag,2013)](https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-0).  I haven't found a Python 3 based book that is as good as this particular Python 2 book.  Any benefits of using Python 3 vs. Python 2 are far overshadowed by the range of Computer Science depth that this book provides, in a relatively affordable, portable, lightweight book. 
* Web applications with Flask and Heroku.   We'll be able to do some cool stuff with putting our applications on the web if we stick with Python 2.7.    It's much tougher to do this with Python 3 at the moment.

As a side note, the College of Engineering Python course, CMPSC 8, uses Python 3.    I say that only "FYI".  Fortunately, that isn't a constraint on this course.   If you decide to switch to Python 3 later, the transition is easy.  


