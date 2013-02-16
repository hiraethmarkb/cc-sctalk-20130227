# CodeCumbria - Source Control Presentation and Workshop (Feb 27th 2013)

## Overview

Rather than a straight talk, which may necessarily skip over stuff due time constraints, or just end up being to dry and boring the pants off everyone (including me - I'm arguably not the best presenter, but here goes....) I wanted to do something different.

There had been various discussions between folks about how to liven up CodeCumbria meetings, and more importantly get folks involved in a way that may not always be possible with just a talk. One recurring idea was that of a workshop style format, that could be preceeded by a short talk to introduce the topic.

I had been toying with the idea of doing a talk on Source Control for awhile, but had been strugling on finding a way to try and make it more interesting. It was during a discussion with Steve at one of the short lived Open Source Cumbria meetings, that the idea for using the talk/workshop format was raised (by Steve). I liked the idea, and thought on it for awhile, and well, here is the result.

As audience participation is desired, there are a few pre-requisites. Namely a laptop with Git installed. As an optional extra (but not entirely necessary), you can signup for a Github account. 

I only ask for Git, as it's what I use, and what I'm more familiar with and therefore easier to base a workshop on. I don't hold to putting any quasi-religious bent on whatever tools you use.

Hopefully you'll get the base concepts and will be able to put them to use with whatever source control system you may choose to use. If indeed, you choose to use one at all, although I would recommend them to the death.

By way of an example, the presentation source files are hosted in this Github repository, and we will be using them for the workshop.

## Instructions

While there are undoubtedly many GUI fine tools available, we will be using the commandline (sorry, GUI-fans!). There's nothing wrong with using a GUI, using the commandline means we are working (a hopefully) with a more consistent experienceacross whatever your platform of choice. It can also help to provide, I think anyway, a better understanding of what you are doing.

Anyway, onto the installs! (Taken from http://git-scm.com/book/en/Getting-Started-Installing-Git)

### Installing on Linux

If you want to install Git on Linux via a binary installer, you can generally do so through the basic package-management tool that comes with your distribution. If you’re on Fedora, you can use yum:

$ yum install git-core
Or if you’re on a Debian-based distribution like Ubuntu, try apt-get:

$ apt-get install git

### Installing on Mac

There are two easy ways to install Git on a Mac. The easiest is to use the graphical Git installer, which you can download from the Google Code page http://code.google.com/p/git-osx-installer

The other major way is to install Git via MacPorts (http://www.macports.org). If you have MacPorts installed, install Git via

$ sudo port install git-core +svn +doc +bash_completion +gitweb

You don’t have to add all the extras, but you’ll probably want to include +svn in case you ever have to use Git with Subversion repositories (see Chapter 8).

### Installing on Windows

Installing Git on Windows is very easy. The msysGit project has one of the easier installation procedures. Simply download the installer exe file from the Google Code page, and run it: http://code.google.com/p/msysgit

After it’s installed, you have both a command-line version (including an SSH client that will come in handy later) and the standard GUI.

### Optional extra - Create a Github account

Go to https://github.com/, click 'Sign up for free' and follow the prompts to setup a 'Free for open source' account
