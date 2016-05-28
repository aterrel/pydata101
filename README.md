# pydata101
Tutorial PyData 101 for PyCon 2016

Follow along at: http://bit.ly/pydata101  
Ask questions at: http://bit.ly/pydata101-doc  
Run on: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/aterrel/pydata101)

## Basics

Python Level: Novice

Audience: New programmers looking to begin working with datasets, basic statistics, and visualization
Objectives: Learn how to use Pandas DataFrames to load and manipulate data, how to use basic classification techniques using SciKit Learn, and how to create interactive visualizations using Bokeh

Description:
Data Science is fun and with the PyData toolset something you can start to build with in an afternoon. Join us as we start with a few datasets, learn how to munge, model, and materialize into simple web applications for predictions. At the end of the day you will come away with a solid understanding of the PyData ecosystem and tools used everyday by data scientists.

## Abstract
Data science applications are all around us. One can find directions on our phones, recommendations on e-commerce sites, or predictions of attacks on our servers. As the uses and opportunities to use data in our applications rise, it becomes an essential skill for programmers to be exposed to the ideas and paradigms of data science applications. We start from the beginning and build out concepts and demonstrations to begin your journey learning the wide world of data science applications.

## LEARNING GOALS
In this tutorial we will start with basic examples of taking raw data and producing insights. A set of exercises with different data properties will be given to help students work through the various challenges that exist working with data. For these tasks we will use the excellent Pandas library that has become the industry standard for representing building data applications.

After we have a good understanding of our data sets and the observations present, we will begin the process of modelling, or predicting, phenomena with that data. Answering questions like "Will it rain today?" or "Will this shopper buy this book?" has never been easier with the Python data ecosystem. Using Scikit Learn, we will explore how to build a model and evaluate its fitness for use in real applications.

Finally, having data and being able to predict phenomena is much less meaningful without a way to communicate it to the world. In the final exercise we will use the up and coming Bokeh library to build interactive visualizations that can be deployed to the web, or viewed on a local machine. By building an interactive exploratory data visualizations, you will be communicating the predictions in a way that appeals to mass audiences.

Come learn the joy of building data applications the PyData way.

## TUTORIAL PREREQUISITE KNOWLEDGE
A basic understanding of the Python programming language and
Understanding of basic mathematics and statistics
Curiosity and willingness to work on real life exercises
## INSTALLATION PREREQUISITES
Basic libraries:
Pandas (http://pandas.pydata.org)
Scikit Learn (http://scikit-learn.org/)
Bokeh (http://bokeh.pydata.org)
Recommended ways to install:
Anaconda (https://www.continuum.io/downloads)
Python 2.7 or Python 3.3+
Using pip from the command line: pip install pandas sklearn bokeh
Your favorite linux package management system
Other useful things to download
IPython notebook (http://ipython.org/notebook.html)
Your favorite census dataset (http://www.census.gov/data/developers/data-sets.html)
An interesting research dataset (https://archive.ics.uci.edu/ml/datasets.html)


##Outline

- Introduction to Jupyter [15 min]
  - What is Jupyter and why
  - Using the notebook to create intactive analysis
  - Sharing notebooks
- Introduction to Pandas [45 min]
  - Reading data
  - Getting a feel of the data
  - Basic statistics
  - Dropping the cruft
  - Quick and dirty visualization
  - The power of the groupby
  - Advance mappings for custom statistics
- Break [5 min]
- Introduction to SciKit Learn [45 min]
  - What is a model
  - How models fit to data
  - Build a few basic models with data from pandas exercises
  - Understanding the error in your model
  - Steps to building better and better models
- Break [5 min]
- Introduction to Bokeh [45 min]
  - Elements of visualization
  - Embedding in a webpage
  - Sending queries to your model from SciKit Learn exercises
- Break [5 min]
- Hacking Challenges [15 min]
  - Putting the above work together in teams with prepared challenges
  - Advanced topics as requested
    - Deep Learning
    - Natural Language Processing
  - Where to learn more
  - Get started with Kaggle

## Installation

There are a lot of ways to install the packages we are going to use for the
course. Our recommendation is to use [Anaconda](http://anaconda.org) and its
package manger [conda](http://conda.org) to get started. You can then integrate
the packages into your own python environment later.

### Download Anaconda

See https://www.continuum.io/downloads

### Download Miniconda for a smaller install

The fastest way to install is to download miniconda (a minimal set of packages
to bootstrap a conda environment). The steps to do so are the following:

- Download the appropriate installer file at http://conda.pydata.org/miniconda.html
- Open a terminal application and run the file (see http://conda.pydata.org/docs/install/quick.html)
- Open a new terminal, go to the directory containing this code and run:
```
$ conda env create
```

This will create an environment with the following packages:

- Python3,
- [pandas](http://pandas.pydata.org/),
- [scikit-learn](http://scikit-learn.org/),
- [bokeh](http://bokeh.pydata.org/),
- [Jupyter](http://jupyter.org/),
- [seaborn](https://web.stanford.edu/~mwaskom/software/seaborn/),
- [pip](https://pip.pypa.io)

Finally we tell your terminal to use this created environment. Do this for
every new terminal that you use this project for.
```
$ source activate pydata101
```

To get started, open your terminal app, navigate to this directory and execute:
```
$ jupyter notebook
```
