# GIThelp
a list of all of my help documents for git!

-handy tutorial:        http://vallandingham.me/Quick_Git.html

###Set up git repository from local computer by typing this in a terminal:
>>> git clone 'https://github.com/tdwilkinson/stellar-analysis.git'

###You have to make a fork before you can suggest a change to someone's code:

-make a fork:           https://help.github.com/articles/fork-a-repo/

-keep fork up-to-date:  https://help.github.com/articles/syncing-a-fork/

###Make commits often, then push code when things work out.
Make sure local files are up-to-date with online files:
>>> git pull

-pull request help:          https://help.github.com/articles/using-pull-requests/

###After making edits to local file, add it to files to be pushed, add commit comments, and push to online files:
>>> git add stellar_analysis.py

>>> git commit -m 'added some stuffs'

>>> git push

### [Change origin of forked repository](https://help.github.com/articles/changing-a-remote-s-url/)
>>> git remote -v         

### Branching
- Keep your master branch clean by [managing your branches.](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

### Reset a Repository
- sets back match the [original repository](http://stackoverflow.com/questions/33119211/git-reset-forked-repo-to-current-copy-of-upstream-repo)

###When using git from a new computer, you have to authenticate it:

### [Markdown](https://guides.github.com/features/mastering-markdown/) help

-generating ssh key:    https://help.github.com/articles/generating-ssh-keys/
##########################################################################
IF HTTP error on push:

go into .git/config file and change remote 'origin' from:
url=https://MichaelDrogalis@github.com/derekerdmann/lunch_call.git 

to:
url=ssh://git@github.com/derekerdmann/lunch_call.git
It works!  Do not forget the "git" before the "@".

###########################################################################
