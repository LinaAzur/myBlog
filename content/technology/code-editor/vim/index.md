---
title: "Vim"
description: ""
date: 2023-07-04
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

It turns on "detection", "plugin" and "indent" at once.

## Shortcuts in vim
To use this shortcuts you have to press esc at least twice, just to make sure you are in normal mode.

```gg```
Works to go to the begining of the file.

```G```
Goes to the end of the file.

```[number] gg```
Goes directly to that line in th file.

``` dd ```
Cut the line where the cursor is currently in.

``` yy ```
Copy the line where the cursor is currently in.

``` p ``` 
Paste the line previously cutted or copied.

``` o ```
Add a new line and go to insert mode

``` i ```
Go to insert mode.

```control + v```
Go to visual block. 
- In this mode you can edit by selecting all the rows you wan tto modify and then press **shift + i** then do the modify and then press esc twice.

```u```
Undo the last change.

```control + r```
Redo the changes

```x```
Delete the character where the cursor is currently in.

```h j k l```
You can navegate throwghout the file with this keys. 
- **h** moves the cursor to the left
- **j** down
- **k** up
- **l** right
