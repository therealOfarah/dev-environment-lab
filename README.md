# dev-environment-lab
<img src ="https://i.imgur.com/Rl5k1yf.png"/>
## OS

darwin21.0

## Shell

/bin/zsh

## zsh location

/bin/zsh

## code alias

/usr/local/bin/code

## GitHub CLI version


## npm version

8.5.5

## node version

v16.15.0

## nodemon version


## Heroku version


## Git version

git version 2.32.1 (Apple Git-133)

## Git email

omaarfaarah2019@gmail.com

## Git Default Branch

main

## Git Merge Behavior

false

## Global Git Ignore

/Users/omar/.gitignore_global

## Contents of ~/.gitignore_global

# This is a list of rules for ignoring files in every Git repository on your 
# computer. See https://help.github.com/articles/ignoring-files

# GitHub maintains a repository of items that can generally be gitignored 
# globally safely at: https://github.com/github/gitignore/tree/master/Global

# GitHub also maintains a repository of language-specific items that should
# typically be ignored on a per-project basis with a .gitignore in that
# project's root directory. 
# This repository can be found at: https://github.com/github/gitignore

# This file DOES include items that would typically not be gitignored globally
# for simplicity during the course, but this may cause issues as you further
# your education post-SEI. These items are denoted when used here and are kept 
# to a minimum.

###############################################################################
#   The items in this section are generally safe be globally gitignored and   #
#         are very unlikely to cause projects to break if left here.          #
###############################################################################

#================================= Archives ==================================#
#                Unpack these files and commit the raw source.                #
#                git has its own built in compression methods.                #

# Compressed Files #
*.7z
*.jar
*.rar
*.zip
*.gz
*.gzip
*.tgz
*.bzip
*.bzip2
*.bz2
*.xz
*.lzma
*.cab
*.xar

# Packing-only formats #
*.iso
*.tar

# Package management formats #
*.dmg
*.xpi
*.gem
*.egg
*.deb
*.rpm
*.msi
*.msix
*.msm
*.msp
*.txz

#===================== Operating System Generated Files ======================#
#----------------------------------- Linux -----------------------------------#
# Temporary files created as backups by text editors or similar programs #
*~

# Temporary files created if a process is still accessing a deleted file #
.fuse_hidden*
.nfs*

# KDE directory preferences #
.directory

# Linux trash folder which might appear on any partition or disk #
.Trash-*

#----------------------------------- macOS -----------------------------------#
# General #
.DS_Store
.DS_Store?
.AppleDouble
.LSOverride

# Thumbnails #
._*

# Files that might appear in the root of a volume #
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share #
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

#---------------------------------- Windows ----------------------------------#
# Windows thumbnail cache files #
Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file #
*.stackdump

# Folder config file #
[Dd]esktop.ini

# Recycle Bin used on file shares #
$RECYCLE.BIN/

# Windows shortcuts #
*.lnk

#==================================== Tags ===================================#
# Ignore tags created by etags, ctags, gtags (GNU global) and cscope #
tags

#============================ Visual Studio Code =============================#
# .vscode excluding certain .json files #
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json

# Local History for Visual Studio Code #
.history/

###############################################################################
#   The items in this section may not typically be gitignored globally and    #
#               may cause future projects to break if left here.              #
# ** However, if you remove them from here, you MUST add them back to the **  #
#  ** projects they apply to by placing a .gitignore containing the items **  #
#           ** to be gitignored in each project's root directory. **          #
###############################################################################

#=========================== Compiled Source Code ============================#
# Class Files #
*.class

# Dynamic Libraries #
*.so
*.dylib
*.dll

# Executables #
*.com
*.exe
*.out
*.app

# Object Files #
*.slo
*.lo
*.o
*.obj

#================================== Django ===================================#
# Logs #
*.log

# Local django settings #
local_settings.py

# SQL database #
db.sqlite3
db.sqlite3-journal

#============================== Node and Python ==============================#
# Environment variables #
.env

#=================================== Node ====================================#
# Dependencies #
node_modules

#================================== Python ===================================#
# Byte-compiled #
*.py[cd]
__pycache__/
.python-version

#================================== React ====================================#
.eslintcache
## Contents of ~/.zshrc

# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:/usr/local/bin:$PATH

# Path to your oh-my-zsh installation.
export ZSH="$HOME/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
ZSH_THEME="robbyrussell"

# Set list of themes to pick from when loading at random
# Setting this variable when ZSH_THEME=random will cause zsh to load
# a theme from this variable instead of looking in $ZSH/themes/
# If set to an empty array, this variable will have no effect.
# ZSH_THEME_RANDOM_CANDIDATES=( "robbyrussell" "agnoster" )

# Uncomment the following line to use case-sensitive completion.
# CASE_SENSITIVE="true"

# Uncomment the following line to use hyphen-insensitive completion.
# Case-sensitive completion must be off. _ and - will be interchangeable.
# HYPHEN_INSENSITIVE="true"

# Uncomment one of the following lines to change the auto-update behavior
# zstyle ':omz:update' mode disabled  # disable automatic updates
# zstyle ':omz:update' mode auto      # update automatically without asking
# zstyle ':omz:update' mode reminder  # just remind me to update when it's time

# Uncomment the following line to change how often to auto-update (in days).
# zstyle ':omz:update' frequency 13

# Uncomment the following line if pasting URLs and other text is messed up.
# DISABLE_MAGIC_FUNCTIONS="true"

# Uncomment the following line to disable colors in ls.
# DISABLE_LS_COLORS="true"

# Uncomment the following line to disable auto-setting terminal title.
# DISABLE_AUTO_TITLE="true"

# Uncomment the following line to enable command auto-correction.
# ENABLE_CORRECTION="true"

# Uncomment the following line to display red dots whilst waiting for completion.
# You can also set it to another string to have that shown instead of the default red dots.
# e.g. COMPLETION_WAITING_DOTS="%F{yellow}waiting...%f"
# Caution: this setting can cause issues with multiline prompts in zsh < 5.7.1 (see #5765)
# COMPLETION_WAITING_DOTS="true"

# Uncomment the following line if you want to disable marking untracked files
# under VCS as dirty. This makes repository status check for large repositories
# much, much faster.
# DISABLE_UNTRACKED_FILES_DIRTY="true"

# Uncomment the following line if you want to change the command execution time
# stamp shown in the history command output.
# You can set one of the optional three formats:
# "mm/dd/yyyy"|"dd.mm.yyyy"|"yyyy-mm-dd"
# or set a custom format using the strftime function format specifications,
# see 'man strftime' for details.
# HIST_STAMPS="mm/dd/yyyy"

# Would you like to use another custom folder than $ZSH/custom?
# ZSH_CUSTOM=/path/to/new-custom-folder

# Which plugins would you like to load?
# Standard plugins can be found in $ZSH/plugins/
# Custom plugins may be added to $ZSH_CUSTOM/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
# Add wisely, as too many plugins slow down shell startup.
plugins=(git)

source $ZSH/oh-my-zsh.sh

# User configuration

# export MANPATH="/usr/local/man:$MANPATH"

# You may need to manually set your language environment
# export LANG=en_US.UTF-8

# Preferred editor for local and remote sessions
# if [[ -n $SSH_CONNECTION ]]; then
#   export EDITOR='vim'
# else
#   export EDITOR='mvim'
# fi

# Compilation flags
# export ARCHFLAGS="-arch x86_64"

# Set personal aliases, overriding those provided by oh-my-zsh libs,
# plugins, and themes. Aliases can be placed here, though oh-my-zsh
# users are encouraged to define aliases within the ZSH_CUSTOM folder.
# For a full list of active aliases, run `alias`.
#
# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"
