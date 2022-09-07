# ME 701 -- Homework 1 -- Grace Wojcik

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

I have been looking for a way to edit pdfs for free without purchasing Adobe Acrobat Pro. 
I use pdf editors all the time for the class that I help teach. Things as simple as reordering
pages or changing old document titles is very frustrating without a proper pdf editor. I found
an alternative online called LibreOffice Draw. I tried to find out how to install it on Linux
and found some promising source code download links, but I could not get it to install on 
ubuntu. I will likely try to install this software again and may even recommend it to my
students if it works for the purposes that I need.


## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

```
top    # Shows the top processes on the system 
       # Sorted by CPU activity
ps     # shows a quick display of a few processes, just the process associated     # with the current terminal session

       
```

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution


To display programs in order of processing and memory I used:
```
top    # Shows the top processes sorted by CPU activity
m      # while in the screen for top pressing m will give memory information


```

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution


To locate bash I used:
```
which bash    $ which is a command that returns the location of the following
              $ bash is located in usr/bin/bash
```
To find my bash version I used:
```
bash –version $ this returns the version and other information on bash 
              $ I have GNU bash, version 5.0.16(1) 

```
