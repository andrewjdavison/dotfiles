# My Dotfiles

It's a terminal thing. You really want to know?

## Prerequisites

I used these to kick start

 * [Vundle](https://github.com/gmarik/vundle) (No longer using janus)
   Install handled by install script
 * [antigen](https://github.com/zsh-users/antigen)
   Install handled by install script
 * [tmux](http://tmux.sourceforge.net/
   preinstall for latest build:
      sudo apt-get install libevent-dev
      sudo apt-get install libncurses-dev
      
   can be installed: `brew install tmux`
 * [tmuxinator](https://github.com/aziz/tmuxinator)
   `gem install tmuxinator`

## Install

   * Make sure libevent-dev is installed
   * MAke sure ncurses is installes
   

 * clone the repo so the contents end up in `~/dotfiles`
 * run the install script: `cd dotfiles && chmod +x install.sh && ./install.sh`

## Other bits

I haven't included the tmuxinator config as they are (private) project
specific. The `tmux.conf` is not very interesting and put together by
googling. My zsh theme is a modification of an existing one, but I don't
remember which.

The battery script is basically taken from
https://github.com/Goles/Battery with minor tweaks and removing spark
usage.

