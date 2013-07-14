# MadLab Simple Dotfiles
This project contains some bash customization files that help [MadLab.com](http://www.madlab.com) developers to be more productive on the command line. 

##Why Use These?
There are thousands of dotfile projects on github. However, many are fairly 'heavy', requiring things like rake, macports, homebrew, or zsh. These are all things that are not part of our standard toolbox. As such, we've customized the command line just with a couple files. 


##Features
###Shell
We've customized the command prompt, and changed the default behavior of `ls` to look nicer. We've also made some aliases for commonly used command options. 
###Sublime Text
Sublime Text is our favorite text editor. We aren't hardcore VIM users here at MadLab. As such, we've set sublime text to be the default editor. This is useful primarily when dealing with git commit/merge messages. 

The command `st` has been aliased to launch sublime text as well, rather then the more standard 'subl'. 
###Git
The majority of customizations are for git. When it a git directory, the command prompt will tell you what branch you are currently in, and what the status is. 

We've also included git-completion, which allows you to autocomplete git commands and branch names using the tab key (just like how file/foldername completion works in bash). 

##Installation
Installation should be very straight forward. If you really want to, you can clone the project, then make symlinks to the files in the home directory. However, the easiest way would probably be to just copy/paste the file contents manually. There are only 3 files you need, .bashrc, .bash_profile, and .git-completion.sh

#Make It Yours!
A developer's dotfiles are very personal - like a pair of underwear! Please fork this project, or otherwise take from it what you like, and make your dotfiles your own. 