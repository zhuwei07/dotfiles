Dotfiles
========

My .bash_profile and terminal settings for OS X, however most things should work under linux.
Colors based on [ahmetsulek's Flat Terminal](https://github.com/ahmetsulek/flat-terminal)

![preview](preview.png)

###Installation
- Put the .bash_profile into your home directory (`cd ~`)
- Open the .terminal file and change terminal profile preferences to set it as the default
- Don't forget to customise the user specific aliases and settings at the top of *.bash_profile*


###### Alternatively use a sym link
Navigate to where you've chosen to placed the files or cloned the repo and run:

```bash
ln -s $(pwd)/.bash_profile $HOME/.bash_profile
```

###Aliases & Features
- **s** - *opens a file in sublime text*
- **o** - *short for open. 'o .' opens the current directory in finder* 
- **highlight** *\<file\>* - *syntax highlighting in terminal*
- **show** / **hide** - *show/hide hidden files*
- **trash** *\<file\>* - *move file to trash*
- **l** - *list all files inclduing dotfiles, in long format*
- **lsd** - *list only directories*
- **deleteExtraBashScripts** - *clears auto-installed bash-scripts*

######navigation
- **desktop** - *cd ~/Desktop*
- **..** 	- *cd ..*
- **...** 	- *cd ../..*
- **....** 	- *cd ../../..*
- **.....** - *cd ../../../..*
- **bk** - *go back a directory*

######git
- **gs** - *git status*
- **ga** - *git add .*
- **gc** - *git commit -m*
- **gca** - *git commit -a -m*
- **push** - *git push*
- **pull** - *git pull*
- **gitsetup** *<repo-url>* - *initalises repo with a given url*

###Auto-installed scripts

Additional scripts installed into ~/.bash_scripts/ on first run

- [git-completion](https://github.com/git/git/tree/master/contrib/completion) - Autocomplete for git from github 's main repoistory
- [z jump script](https://github.com/rupa/z) - 'Tracks your most used directories, based on frequency'
- [trash](https://github.com/morgant/tools-osx) - 'trash allows trashing of files instead of tempting fate with rm'

###Dependencies

- [pygmentize](http://pygments.org/) for syntax highlighting in terminal (use bash alias **c** *\<file\>*) can be installed with `sudo easy_install Pygments`
