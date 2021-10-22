# VIM Cheatsheet


## Install Vim

* Open terminal application. You can also press CTRL+ALT+T keyboard shortcut
* Update package database by typing the ```sudo apt-get update``` command
* Install vim on Ubuntu Linux, type: ```sudo apt-get install vim```
* Verify vim installation by typing the ```vim --version``` command
* Open vim by typing ```vim``` or Open a file in vim by typing ```vim filename```


## Mode Switching

* From Normal mode press ```i```          -> Takes vim to insert mode
* From Any mode press ```ESC```           -> Takes vim to Normal mode
* From Normal mode press ```v```          -> Takes vim to Visual mode
* From Visual mode press ```ESC ESC```    -> Takes vim to Normal mode


<br>

## Vim Commands

> ***Note : Your vim needs to be in Normal/Command mode to execute all the commands listed below.***

<br>

### Save and Exit

* ```w```     -> Save
* ```q```     -> Exit
* ```q!```    -> Force Exit
* ```wa```    -> Save all
* ```wq```    -> Save and exit
* ```wqa```   -> Save and exit all

### Cursor Movement

* ```h```    -> Move cursor left
* ```j```    -> Move cursor down
* ```k```    -> Move cursor up
* ```l```    -> Move cursor right
* ```5j```   -> Move cursor 5 lines down
* ```5k```   -> Move cursor 5 lines up
* ```5h```   -> Move cursor 5 characters left
* ```5l```   -> Move cursor 5 characters right
* ```5G```   -> Move cursor to line number 5
* ```gg```   -> Move cursor to first line
* ```G```    -> Move cursor to last line
* ```0```    -> Move cursor to beginning of line
* ```$```    -> Move cursor to end of line
* ```%```    -> Find bracket pair
* ```H```    -> Move cursor to screen top
* ```M```    -> Move cursor to screen middle
* ```%```    -> Move cursor to screen bottom

### Cut, Copy, Paste and Delete

* ```yy```     -> Copy a line
* ```5yy```    -> Copy 5 lines
* ```cc```     -> Cut a line
* ```5cc```    -> Cut 5 lines
* ```p```      -> Paste the copied text
* ```dd```     -> Delete a line
* ```5d```     -> Delete 5 lines


### Undo and Redo

* ```u```              -> Undo
* ```Ctrl + r ```      -> Redo

### Search and replace

* ```/pattern```       -> Search for pattern
* ```?pattern```       -> Search backward for pattern
* ```n```              -> Repeat search in same direction
* ```N```              -> Repeat search in opposite direction
* ```:%s/old/new/g```  -> Replace all old with new throughout file 
* ```:%s/old/new/gc``` -> Replace all old with new throughout file with confirmations

### Working with multiple files

* ```:e file```       -> Edit a file in a new buffer 
* ```:sp file```      -> Open a file in a new buffer and split window
* ```:vs file```      -> Open a file in a new buffer and vertically split window
* ```:Explore```      -> Open file explorer
* ```Ctrl + ww```     -> Switch windows

### Tabs

* ```:tabnew file```  -> Open a file in a new tab 
* ```gt```            -> Move to next tab 
* ```gT```            -> Move to previous tab
* ```#gt```           -> Move to tab number #

<br>

# Authors
- [Aadarsha Dhakal](https://github.com/aadarshadhakalg/)
- [Ayush Paudel](https://github.com/AyushPaudel/)

<br>

# MIT License

Copyright (c) 2021 Green Club of Thoughts

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.