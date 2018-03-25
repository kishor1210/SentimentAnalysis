# SentimentAnalysis

DESCRIPTION:
In this article we will:

Extract twitter data using tweepy and learn how to handle it using pandas.
Do some basic statistics and visualizations with numpy, matplotlib and seaborn.
Do sentiment analysis of extracted (Trump's) tweets using textblob.



What will we need?

First of all, we need to have Python installed. 
I'm almost sure that all the code will run in Python 2.7, but I'll use Python 3.6. I highly recommend to install Anaconda, which is a very useful Python distribution to manage packages that includes a lot of useful tools, such as Jupyter Notebooks. I'll explain the code supposing that we will be using a Jupyter Notebook, but the code will run if you are programming a simple script from your text editor. You'll just need to adapt it (it's not hard).


The requirements that we'll need to install are:


NumPy: This is the fundamental package for scientific computing with Python. Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data.

Pandas: This is an open source library providing high-performance, easy-to-use data structures and data analysis tools.
Tweepy: This is an easy-to-use Python library for accessing the Twitter API.

Matplotlib: This is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.

Seaborn: This is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.

Textblob: This is a Python library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks.

All of them are "pip installable". At the end of this article you'll be able to find more references about this Python libraries.

Now that we have all the requirements, let's get started!
