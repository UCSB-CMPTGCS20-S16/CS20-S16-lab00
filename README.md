# CS20-S16-lab00
https://github.com/UCSB-CMPTGCS20-S16/CS20-S16-lab00

CMPTGCS 20, S15, lab00:  Hello World in Python 2.7

For this lab, there is one goal: write a Python 2.7 program that prints the string `Hello, World!` as its output.

In this sense, we are following a long tradition: for 
[more than 40 years](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)
it has been a tradition to make printing `Hello, World!` be the first
thing you do when learning a new programming language.

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

## Be sure you get Python 2, not Python 3

* BE SURE YOU GET PYTHON 2.7.11 (or a later version on the 2.7 branch.)  
* FOR THIS COURSE, YOU DO NOT WANT ANY VERSION OF PYTHON STARTING WITH 3.

If you already have a version of Python 3 on your system, that's ok.  

Supposedly, Python 2 and Python 3 can happily co-exist.   What's this all about?  We'll explain in lecture, but if you missed the lecture, or want to learn more, here's some information: https://wiki.python.org/moin/Python2orPython3

As for why we are using Python 2 rather than 3 in this course, the answer is:
* The [textbook we are using (Guttag,2013)](https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-0).  I haven't found a Python 3 based book that is as good as this particular Python 2 book.  Any benefits of using Python 3 vs. Python 2 are far overshadowed by the range of Computer Science depth that this book provides, in a relatively affordable, portable, lightweight book. 
* Web applications with Flask and Heroku.   We'll be able to do some cool stuff with putting our applications on the web if we stick with Python 2.7.    It's much tougher to do this with Python 3 at the moment.

As a side note, the College of Engineering Python course, CMPSC 8, uses Python 3.    I say that only "FYI".  Fortunately, that isn't a constraint on this course.   If you decide to switch to Python 3 later, the transition is easy.  

# Once you've downloaded Python 2.7.11, Start up Idle and enter your hello.py program

You should have gotten a program along with your Python 2.7.11 download called "Idle".

Idle is a program that allows you to create and modify Python programs.   It also allows you to check the program for formatting errors (syntax errors) and then run the program and see what it does.      

I'll demonstrate the use of Idle in lecture, since its much easier to just follow along than to try to explain everything in a text document.   But if you need a demonstration, you can find one on YouTube.  For example: http://www.youtube.com/watch?v=Cdk20r2dgFU

We are going to put our hello.py into Idle, and run it.

# Uploading your program to submit.cs

Next, we'll try submitting our program to submit.cs, which is an autograder system used by many Computer Science department courses at UCSB.    

As this is a CCS course, we aren't really concerned about "grades", per se, so perhaps "autograder" is a misnomer in our case.  Rather, this is a system where we can check the correctness of our solution, and thereby check our understanding of what we are trying to learn.

# Creating your submit.cs account

You may have already done the steps in this section--an email was sent out through Gauchospace inviting you to do so.   If you have, you may skip this section.

Otherwise, to create your submit.cs account, please take the following steps:

1. Navigate to the following website: https://submit.cs.ucsb.edu
1. Click on the "Create User" button, and enter your Umail address.
1. Check your umail for a message with additional instructions—follow the instruction in the email to select a password and activate your account.
1. Go back to the website: https://submit.cs.ucsb.edu and login with your account.
1. Select "Join Class", and click on the link for CCS_CMPTGCS_20_s16

At that point, you should be good to go.

# Navigate to the page for submitting lab00

The page for submitting lab00 is here: https://submit.cs.ucsb.edu/form/project/452/submission

Navigate to that page, and upload your `hello.py` file.

Note that if you try to upload a file with a name that does not match EXACTLY the name `hello.py`, the system will not allow you to do it.  The name cannot be, for example, `Hello.py`, or `HelloWorld.py`, or `hell0.py` (note the zero as in '007' instead of the letter 'o' as in octopus.)  Only `hello.py` is permitted.   This will always be the case with submit.cs: it is very picky about the filename that it wants.

Once you upload it, you should get a page that shows your submission is pending.

Refresh that page, and you should get one that indicates with either red, or green, whether the test cases for your code passed or failed.

If you got all green, and 100 points, then you passed, and you are finished with lab00!

