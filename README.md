# a1-news

## Overview

Congrats!  This is your first problem set in INFO201.
In this exercise, you're going to create a simple markdown page that
summarizes a current event.  This problem set has several aims:

1. To get you started with git and GitHub for project management.
   This is something all developers need.
3. Get some experience with command line to navigate your file system
   and create folders.  Although you can manage most of everyday tasks
   without command line, it is an invaluable tool for more specific
   tasks, and when working with various backend solutions.
3. Learn to write simple nicely formatted markup text

The instructions below detail how to complete this assignment, and in
the end it should look [something like this](example.png) (though with your chosen
event):

This introductory assignment includes two main tasks:

**First**, you have to edit this `README.md` file to create a
Markdown document that describes a news story. 

**Second**, you'll keep track of the terminal commands you run in the
`session.sh` file (you don't need to run that file).  This is not
something that is commonly done, but we would like to see how
comfortable you are with command line.

**Finally**, when you're done, please **delete these instructions**
and leave only the markdown news story that you've written.  Make sure
to **commit** and **push** your edits to github and **submit your
repo's GitHub URL** to Canvas on time for full credit.


## Detailed Instructions

In order to complete this assignment you'll be editing two files:

* _README.md_: The  file that renders your news page
* _session.sh_: A file in which you'll keep track of your terminal
  commands (not something that you typically do, but that will allow
  us to see how comfortable you are with command line).
  
Pick a text editor, both Atom and RStudio are good choices.


### Set Up

At this point, you should have a GitHub account set up, and should
feel (somewhat) comfortable using basic git commands in your
terminal. Follow the link on canvas to create your own private
repository for this assignment. This should automatically create a
private repository with your name in the course organization. This is
the URL that you will submit to Canvas as your assignment. You will
work directly in this repository that lives in the course GitHub
organization, so you do not need to fork it any more--clicking the
link essentially forks it.  You have just to clone it to your
machine before you start working.

Inside of your assignment repository on GitHub, you should see a
_session.sh_ file. This file contains the instructions for managing your
project, such as creating folders from the terminal and tracking your
files with Git.  These are broadly the steps that you should do on
your terminal, but you may choose to do some step differently.

### README.md

Your README.md file is the file in which you will perform the majority
of the assignment. You'll write the syntax necessary to create the
overview of your current event. More specifically, you'll do the
following:

* Create a top level heading that serves as a headline of your current event
* Write a short introductory paragraph the news event. You should
  emphasize certain words by using both bold and italics.
* Include a quote from the news article, formatting it as a blockquote.
* Display an image related to your article.  You should create a
  _imgs/_ folder in the current project directory using command line,
  and thereafter download an image file
  from the web into it.  Don't forget to add it to git!
  **Note**: the example image here is _not_ in the _imgs/_
  directory! 
* Create an unordered list of additional information about your event,
  each of which should reference (i.e. contain an url link) a
  different news source.  There should be at least 3 different sources
  listed. 
* Commit your work (including edits/added files) every once and a
  while.  Your final submission should include at least 5 committed
  changes. 


### Submission

Once you've finished editing your README.md file, use git to add and
commit the changes you've made, and push those changes to your
repository on GitHub (these instructions are in your session.sh
file).  Check out your repo's GitHub page and ensure the story looks
right.  In particular, the image should be visible.

Finally, **please submit the URL of your GitHub Repository** as you
assignment submission on Canvas in time!


## Grading


### README.md File (**32 points**)

- **Top level header**: 4 points (-1 for other header type)
- **Summary paragraph**: 5 points (-1 if < 2 sentences, -1 if no bold, -1 if no italics)
- **Block quote**: 5 points (-2 for improper formatting)
- **Image**: 10 points
    - -2 if image not stored in a separate directory
    - -1 if folder is not called `imgs`
    - -2 if _relative path_ isn't used or http path was used
    - -2 if image doesn't render on github
- **Unordered list of different sources**: 8 points 
    - -2 if not unordered list
	- 2 points for each item in list: -1 if url source link
      missing/not working.


### session.sh File (**13 points**)

- Print your working directory (**1 point**)

- Change your directory to a folder in which you do work for this class (Make sure to use the "~" shortcut) (**2 point**)
    - -1 if the `~` isn't used

- Clone your private assignment repository from GitHub to your machine (**1 points**)

- Change your directory to inside of your a1-news-USERNAME repository (**1 points**)

- Make a new folder called "imgs" (**2 points**)

- Add all of your changes that you've made to git (**2 points**)

- Make a commit, including a descriptive message(**2 points**)

- Push your change up to GitHub(**2 points**)


### github repo (**5 points**)

- -2 if HEAD (i.e. the current version of _master_-branch) contains
   unnecessary/unrelated files (such as _.DS\_Store_).
- -1 if committed less than 5 times, -2 if committed only once.

---

Have fun!
