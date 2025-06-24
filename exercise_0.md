##########################################################################
#
# Welcome to Exercise 0! 
#
# This exercise is focused on navigating a computer's filesystem through
# the command line. 
#
# NOTE ON DIRECTORIES:
# The 'base' directory that we will be working from is called
# command_line_reu. 
# This should not be confused with the 'root' directory of the filesystem
# which is denoted by `/`.
# If you are on Quest (Northwestern's High Performance Compute (HPC) 
# cluster), the full path to command_line_reu is:
# `/projects/e32894/command_line_reu`
# If you are not on Quest and have cloned command_line_reu from GitHub,
# the full path to command_line_reu will depend on where in your
# computer's filesystem you ran your `git clone` command from.  
#
# NOTE ON SYNTAX:
# Here, commmands (to be run in your terminal) will be enclosed in 
# `tick marks`. If you are copy-pasting the commands from this file into 
# your command line, do not include the tick marks. 
# Also, any text enclosed in <angle_brackets> is a placeholder and should
# be replaced with your particular value. For example, given the command 
# `ssh <NetID>@login.quest.northwestern.edu`, if my NetID is pie123, 
# I would execute the command `ssh pie123@login.quest.northwestern.edu`
#
# NOTE ON OPTIONS/FLAGS, AND ARGUMENTS:
# Many commands that you will run in your terminal take extra options 
# (through flags) that alter what the command does as well as its output. 
# Commands also take (or require) certain inputs called arguments. 
# For example, in the command `ls -l --all /projects/e32894`, we are 
# passing options using the `-l` and `--all` flags and we are providing
# the value `/projects/e32894` as an argument.   
#
##########################################################################
#
# 1. Where am I? 
#
# When navigating a computer's filesystem, it is helpful to know what 
# your current working directory is. In other words, where you currently 
# 'are' in the filesystem. 
# The command that prints your current working directory is `pwd`
# `pwd` stands for Print Working Directory. 
# 
# --> Run `pwd` and examine the output. 
#
# NOTE ON OUTPUT OF `pwd`:
# By now you may be familiar with the concept of a full path vs. a 
# relative path. A full path specifies the exact location of a file or
# directory starting from the systems root directory /. A relative path 
# specifies the location of a file or directory relative to your current 
# working directory. 
# `pwd` returns the full path of your current working directory.
# 
##########################################################################
#
# 2. What is here?
# 
# To view the contents of your current working directory, use the command
# `ls`. `ls` is short for list. 
#
# --> Run `ls` and examine the output. 
# 
# `ls` can take several different options that ask it to provide more 
# detailed information. 
# 
# --> Run `ls -a` and `ls -l` and examine the output. What has changed?
#
# You can also use `ls` to list the contents of a directory other than 
# your current working directory. 
#
# --> Run `ls <path_to_repo>/command_line_reu/labyrinth/stable/donkeys`,
#     replacing <path_to_repo> with either `/projects/e32894` or the 
#     location of command_line_reu on your computer. What is the content
#     of the donkeys directory?
#
# --> Run the same command as above, while passing the `-a` and `-l` 
#     flags together. 
#     `ls -la <path_to_repo>/command_line_reu/labyrinth/stable/donkeys`
#     what is different about the output?
#
# --> Run `ls <path_to_repo>/command_line_reu/labyrinth/fountain/` and 
#     `ls -a <path_to_repo>/command_line_reu/labyrinth/fountain/`. What
#     is the difference?
#     Note: file and directory names that start with `.` are hidden files
#     and directories. By default, `ls` does not show hidden files or 
#     directories - passing the `-a` flag reveals them.  
#
##########################################################################
#
# 3. How do I go somewhere else?
#
# To move from one location in the filesystem to another, use command
# `cd <path_to_location>`. `cd` stands for Change Directory. 
# 
# When changing directory, you can pass either a full path or a relative
# path as an argument. For example, if we are in the directory 
# command_line_reu and we want to go to the directory donkeys, the
# following two commands are equivalent. 
# `cd <path_to_repo>/command_line_reu/labyrinth/stable/donkeys`
# `cd ./labyrinth/stable/donkeys`
# Here, `.` is shorthand for current working directory.
#
# Similarly `..` is shorthand for the parent (or previous) directory 
# of your current location. Using multiple `..` in a row will move you 
# back multiple directories at a time. 
#
# Last `~` is shorthand for your home directory on the computer you're 
# working on. On Quest, this is `/home/<your_NetID>`. On another computer
# it will be something else. 
# 
# Recall that you can use `pwd` to print your current working directory.
# This is helpful if you ever get lost. 
# 
# --> Run `cd <path_to_repo>/command_line_reu/labyrinth/garden_path` and 
#     then `cd ..`. Where are you now? What happens if you run 
#     `cd <path_to_repo>/command_line_reu/labyrinth/garden_path/../..`?
#
# --> Run `cd <path_to_repo>/command_line_reu/labyrinth/garden_path` and 
#     then `cd bugs`. Where are you now? From bugs, run `cd ../rocks`.
#     Run `cd .`. Does that change anything? 
#
# --> Run `cd <path_to_repo>/command_line_reu/labyrinth/fountain`. How can 
#     you get back to the stable with the donkeys from here? (Hint: there
#     are multiple possible answers). 
#
##########################################################################
# 
# 4. How do I make a new directory? 
#
# New directories can be made with the `mkdir` command. `mkdir` takes as 
# an input argument the name of the directory you'd like to create. 
# 
# While options can be passed to `mkdir` to create nested directories 
# all in one step, the easiest thing to do is to be in the location 
# where you want your new directory to be. 
# 
# In other words, the new directory you create with `mkdir` will be a 
# subdirectory of your current working directory. 
# 
# --> Run `cd <path_to_repo>/command_line_reu/labyrinth/wooded_lane` and 
#     `cd ./meadow/neighborhood`. In the neighborhood directory, make a 
#     folder named after your NetID by running `mkdir <NetID>`. 
#
# --> Now that your NetID folder exists, change directory (`cd`) into it
#     and print the full path of your current working directory using
#     `pwd`. 
#
##########################################################################
#
# 5. Putting it all together (`pwd`, `ls`, `cd`)
# 
# --> From command_line_reu, find the coins in the fountain in the
#     labyrinth. What coins are in there? What is the full path to the 
#     nickles.md file?
#
# --> What is in the fridge in the kitchen in the hobbit house in the 
#     meadow in the wooded lane in the labyrinth?
#     (This is purposefully annyoing)
# 
# --> What are the names of our ponies? What is the full path to where 
#     the ponies live?
#
# --> How would you get from the ponies to the horses? 
#
# --> Do any other exploration you like! Hint: there is hidden treasure 
#     somewhere!!
#
##########################################################################