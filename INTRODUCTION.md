# Introduction

## First of all: thanks! 

### For funding and organization support: 
- To the [CNI](http://cni.stanford.edu/). Bob Dougherty

- To the [neuroscience grad program](http://biosciences.stanford.edu/neurosciences.html). Miriam Goodman, John Huguenard, Ross Colvin and Katie Johnson.

### For organizational and instructional support:
- To [Software Carpentry](http://software-carpentry.org/)

### The instructors and helpers: 

**Instructors**
- Bernhard Konrad
- [Paul Ivanov](http://pirsquared.org/)
- [Ariel Rokem](http://arokem.org)

**Helpers**

What are helpers for? Well, they're here to *help*!

- [Jayanth Raman](https://www.linkedin.com/in/jayanthraman)
- Michael Waskom

## Why are we here?

- People are really good at some things. Computers are very good at other things.
- Don't let your computer do what you could do better.
- But don't bother doing all the things your computer should be doing!

## [The schedule](http://arokem.github.io/boot-camps/2013-05-06-stanford/#schedule)

### In numbers:
- 3-4 hands-on sessions per day
- 2 coffee breaks/day

Coffee breaks will be useful for asking questions and making comments
In particular, please use [this etherpad](https://etherpad.mozilla.org/m4Um2MFlCN)
to make comments and ask questions as we go along.

We will have structured moments throughout the day to go over these questions
- 1 lunch break/day

### Lunch on your own...

# Day 1 - the basics

- The unix shell : the unix shell is a powerful tool for interacting with the contents of your computer. In the shell, atomic operations are strung together to automate routine operations

*"This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface."* -- Doug Mcllroy (via [Wikipedia](http://en.wikipedia.org/wiki/Unix_philosophy))

- Git : Version control or time travel made easy.

- Introduction to python : Python is a programming language that is rapidly becoming the *lingua franca* for many scientific fields. It is relatively easy to learn. Makes easy things easy and difficult things possible. Many libraries help to do the tasks that we want to do as scientists.

# Day 2 - how to make some damage

- Scientific computing in python : We will introduce the numpy library for array computations and the scipy library for performing scientific computations. Matplotlib will be introduced as a way of visualizing data.

- Software validation and testing : before we go on to more advanced data exploration and visualization, we will take a moment to teach you how to verify that your software works. We will use automated testing using the nose library. Test-driven development will be introduced as a way of thinking about writing code.

- Data exploration and analysis: with all the tools at our disposal, we will now attack a scientific question with some data from neuroscience experiments. We will demonstrate how you would build a reproducible work-flow for your computational analysis. 

## Questions?

## Before we move on

Does everyone have everything they need installed?

- Let's open a terminal
- Navigate to an easy to find location on your hard-drive. For example:
    $cd ~/Documents

- And get this repository, by running this command (we will explain this command later this afternoon):
	git clone https://github.com/arokem/boot-camps.git --branch 2013-05-06-stanford --single-branch SWC

- Now change your working directory to the `SWC` directory. The files that we will be using in the workshop (+much more!) should now be in there.
