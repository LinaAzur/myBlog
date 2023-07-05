---
title: "Vim"
description: ""
date: 2023-06-04
cascade:
  showReadingTime: true
---


## Basic vim configuration

You can add these lines inside your **~/.vimrc** to use vim more comfortably. This is just a basic configuration.

``` syntax on ```
This line works to higlight the syntax with colors.

``` set number ```
Works to enumerate the lines of the file.

``` set expandtab ```
To insert spaces whenever the tab key is pressed.

``` set tabstop=2 ```
Control the width of the tab character.

``` set softtabstop=2 ```
Inserts the specified number of spaces when hitting the tab key.

``` set shiftwidth=2 ```
Controls the number of spaces that are inserted for indentation, when you hit enter to go to the next line.

``` set title ```
Displays the name of the currently edited file.

``` set ruler ```
Show the position of the cursor in the lower right corner.

``` set showmode ```
Always show what mode we're currently editing in.

``` color slate ```
Change the color scheme.

``` filetype plugin indent on ```
This is a combination of 3 elements:
- filetype on
- filetype plugin on
- filetype indent on

It turns on "detection", "plugin" and "indent" at once
