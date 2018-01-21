---
layout: post
title: "Python Tutorial, Part 1. Getting started with Python"
description: "Learn how to install Python using Conda"
category: Python Tutorials
tags: [python, tutorial, intro]

author: Matt Murbach
authorlink: http://mattmurbach.com
authorimage: mattmurbach.png

comments: false
share: true
---
## Installing Python using Conda

This page is the first post in a series of introductory python tutorials:
1. Installing Python using Conda - *this tutorial*
2. [Getting started with Jupyter]({% post_url 2018-01-25-getting-started-with-Jupyter %})
3. [Using Python packages]()
4. [Working with data]()
5. [Making figures in Python]()

<hr>

To begin using Python, we first need to install it. For these tutorials, we will be using Python 3.6, although any Python 3 should work. We use Python 3 as it is the "present and future of the language.<sup>[\*](https://wiki.python.org/moin/Python2orPython3)</sup>" ([Python 2 countdown clock](https://pythonclock.org/))

If you do not already have Python 3 installed on your computer (or even if you do, but don't use Conda), we recommend using installing miniconda.
Installation instructions for your OS can be found at [https://conda.io/miniconda.html](https://conda.io/miniconda.html).

*Note:* If you want to be able to use the conda command in the Command Prompt or bash shell, check the Add Conda to PATH box during installation.

After you have installed conda, you can run the following commands in your Terminal/Command Prompt/git bash to update and test your installation:

1. Update conda’s listing of packages for your system: `conda update conda`
2. Test your installation: `conda list`
    - For a successful installation, a list of installed packages appears.
3. Test that Python 3 is your default Python: `python -V`
    - You should see something like `Python 3.6.3 :: Anaconda, Inc.`

You can interact with Python at this point, by simply typing `python`.

Try executing the following statements in this interactive environment:
>>> \>\>\> a = 5 <br>
>>> \>\>\> print(a) <br>
>>> 5 <br>
>>> \>\>\> myName = 'Mark' <br>
>>> \>\>\> print('Hi, my name is {}!'.format(myName)) <br>
>>> Hi, my name is Mark!

To exit out of this interactive Python session, type `exit()`.

If you've made it this far, congratulations!
You now have Python 3 and Conda installed on your computer and you're ready to move on to [Part 2. Getting Started with Jupyter]({% post_url 2018-01-25-getting-started-with-Jupyter %}).
