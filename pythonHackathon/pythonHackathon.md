# Python Hackathon
## Function of Data Science at UCSB Project Group

**Contributors**:
+ Raul Eulogio
+ Nathan Fritter

Necessary to discuss with everyone:
+ Date(s) (Most likely dates since we have a large preference for two dates)
+ Location - On Campus
+ Time
	+ Earliest works best, but how early is the issue
+ Sign-In
+ Pitch in?
	+ Coffee
	+ Snacks?
+ Anything else add here: 

## **Issues to Address**:

The purpose of this file is to address issues with respect to setting up **Python** *before* attending the **Hackathon**. If we have too many people troubleshooting at the **hackathon**, it will lose the purpose of the **hackathon**'s intent, which is to collaborate learning/teaching **Python** for data analysis, not setting it up.

So we are giving a brief overview of what should be done before the **hackathon** so that we will maximize our time in learning **Python**. 

## Downloading Python
Install **Python3.X** onto your computer. 
### Mac OS
**Mac OS** has **Python2.7** pre-installed so download **Python3.X**. Here's a quick run through although we recommend reading this [Guide](http://docs.python-guide.org/en/latest/starting/install/osx/) as well as reading the [Python Docs](https://www.python.org/). 

Installing **Python3.X** (from the command line) using homebrew (a popular package manager) for **Mac OS** would be simply 

	brew python3

That downloads **Python 3.X**, to test this on the terminal run

	python3  

This should open **Python3.X** (If you get an error code, google it and try diagnosing what the issue was or contact us), now run the command 

	quit() 

This should close **Python**. Let's  test out `pip3` (Method we will use extensively for downloading 3rd party modules) by downloading a popular module used for data analysis, pandas:

	pip3 install pandas

And you should see the installment take place, and your set! 

### Windows 
I unfortunately don't have a lot of experience installing **Python** on windows, but here's a tutorial from [The Hitchhiker's Guide to Python's](http://docs.python-guide.org/en/latest/starting/install/win/) guide for doing so. 

**Important**: this guide are instructions for 2.7. this resource will be mentioned later as well (So we think its a good resource if you find any other let us know so we can add it here!)

## Virtual Environments
As you venture into the world of programming and data science it is necessary to use and understand *Virtual Environments*. There are two *Virtual Environments* that we familiar with, choice is really personal taste. 

+ [**Anaconda**](https://www.continuum.io/downloads) - Popular and adverstised as a *Virtual Environment* for data science teams. Last quarter, Jason told people to download this for their *Virtual Environments* so if you have this just go ahead and use it. 
+ [**Virtualenv**](http://docs.python-guide.org/en/latest/dev/virtualenvs/) - This tool is more versatile in that it is not advertised for a specific niche, so `virtualenv` seems to be the *Virtual Environment* used for any **Python** package. If you follow the tutorial provided it should be pretty straightforward to apply and if you have any questions contact me. 

**Recall**: Download `virtualenv` for **Python3.X** using `pip3` not `pip` 

**Important to Note**: The reason we are stressing the importance of using *Virtual Environments* is because we want your code to be reproducible. Once people want to replicate your projects, they need to know what **Python** version you used, they need to know what module versions you used. Often times when not specified someone might try to replicate your project and if they have an older **Python** version, they will quickly run into a lot of error codes, so you'll be doing people a huge favor by specifying what versions of modules and **Python** you used. 

## Conclusion
Please ensure, in order to have the most prodcutive **Hackathon**, you handle these issues **before** the day of:

+ Have **Python3.X** on your computer 
+ Have a *Virtual Environment* set up on your computer (we might be lenient and go about teaching how to work *Virtual Environments* since at first it can be a daunting concept) 