Dotfiles
========

.bash_profile and terminal settings for OS X however most things should work under linux
colors based on [ahmetsulek's Flat Terminal](https://github.com/ahmetsulek/flat-terminal)
![preview](preview.png)

###Installation
- Put the .bash_profile into your home ~ directory
- Open the .terminal file and change terminal preferences to set to default
- Don't forget to customise the user specific aliases and settings at the top of *.bash_profile*


###### Alternatively use a sym link
- Fork
- Configure projects folder and other user-specific stuff at the top of *.bash_profile*
- Navigate to where you've chosen to placed the files or clone the repo and then run:

```bash
ln -s $(pwd)/.bash_profile $HOME/.bash_profile
```

###Dependencies

- [pygmentize](http://pygments.org/) for syntax highlighting in terminal (use bash alias **c** *\<file\>*) can be installed with `sudo easy_install Pygments`

###Auto-installed scripts

These scripts are into ~/bash_scripts

- [git-completion](https://github.com/git/git/tree/master/contrib/completion) - Autocomplete for git from github 's main repoistory
- [z jump script](https://github.com/rupa/z) - 'Tracks your most used directories, based on frequency'

###Aliases & Features
- **s** - *opens a file in sublime text*
- **o** - *short for open, 'o .' to open current directory in finder* 
- **c** *\<file\>* - *syntax highlighting in terminal*
- **show** / **hide** - *show/hide hidden files*
- **la** - *list all files inclduing dotfiles, in long format*
- **lsd** - *list only directories*
- **removeExtraBash** - *clears auto-installed bash-scripts*

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
- **gca** - *git commit -a -m*c
- **gp** - *git push*

