+++
date = "2018-10-23"
draft = false
tags = ["productivity"]
title = "Using Ctrl + Arrow Keys in vim inside tmux"
math = false
summary = ""

[header]
image   = ""
caption = ""

+++

Being a non-expert vim user, I like to use the Ctrl + Arrow Keys to navigate over words.
However, this seems to break when using vim inside tmux.
The simplest fix I could find is to add the following lines to `.tmux.conf`:
```
set-option -g default-terminal "xterm-256color"
set-window-option -g xterm-keys on
```
