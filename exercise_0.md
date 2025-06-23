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
# which is denoted by /.
# If you are on Quest (Northwestern's High Performance Compute (HPC) 
# cluster), the full path to command_line_reu is:
# /projects/e32894/command_line_reu
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

