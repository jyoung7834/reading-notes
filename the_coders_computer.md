


# The Command Line
Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX. This tutorial won't focus on these as I reckon you can probably figure that part out by yourself. This tutorial will focus instead on the command line (also known as a terminal) running Bash.

The command line is an interesting beast, and if you've not used one before, can be a bit daunting. Don't worry, with a bit of practice you'll soon come to see it as your friend. Don't think of it as leaving the GUI behind so much as adding to it. While you can leave the GUI alltogether, most people open up a command line interface just as another window on their desktop (in fact you can have as many open as you like). This is also to our advantage as we can have several command lines open and doing different tasks in each at the same time. We can also easily jump back to the GUI when it suits us. Experiment until you find the setup that suits you best. As an example I will typically have 3 terminals open: 1 in which I do my working, another to bring up ancilliary data and a final one for viewing Manual pages (more on these later).


- user@bash:  ls -1 /home/ryan
- total 3
- drwxr-xr-x 2 ryan users 4096 Mar 23 13:34 bin
- drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
- drwxr-xr-x 2 ryan users 4096 May 05 17:25 public_html
- user@bash:

Let's break it down:

- **Line 1** presents us with a prompt ( user@bash ). After that we entered a command ( ls ). Typically a command is always the first thing you type. After that we have what are referred to as command line arguments ( -l /home/ryan ). Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). The first command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. Options are usually listed before other arguments and typically start with a dash ( - ).
- **Lines 2 - 5** are output from running the command. Most commands produce output and it will be listed straight under the issuing of the command. Other commands just perform their task and don't display any information unless there was an error.
- **Line 6** presents us with a prompt again. After the command has run and the terminal is ready for you to enter another command the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with this).
Your terminal probably won't have line numbers on it. I have just included them here to make it easier to refer to different parts of the material.

## Opening a Terminal
Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. This tutorial will assume you are using bash as your shell.

If you would like to know which shell you are using you may use a command called **echo** to display a system variable stating your current shell. echo is a command which is used to display messages.

1. user@bash: echo $SHELL
2. /bin/bash
3. user@bash:

As long as it prints something to the screen that ends in bash then all is good.

## Shortcuts
The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial. Take note of them as not only do they make your life easier, they often also save you from making silly mistakes such as typos.

### Shortcut
Her's your first shortcut.  When you enter commands, they are actually stored in a history.  You can traverse this histor using the up and down arrow keys.  So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times.  You can also edit these commands using the left and right arrow keys to move the cursor where you want. 

 





