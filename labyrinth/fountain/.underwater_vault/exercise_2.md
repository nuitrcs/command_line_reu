##########################################################################
#
# Welcome to Exercise 2! 
#
# This exercise is focused on using the command line text editor nano to 
# create and edit files. 
# Other command line text editors such as vim and emacs function similarly
# to nano, but have different syntax and shortcuts. 
# 
# A summary of nano's shortcuts is available here: 
# https://www.nano-editor.org/dist/latest/cheatsheet.html
# You can also type CTRL+G while inside nano to view the shortcuts. 
#
# NOTE FOR MAC USERS:
# In the above summary of nano's shortcuts, use ESC instead of ALT.
# Do not hold in ESC, just press it once and then press the following 
# key in the shortcut.
# For shortcuts with CTRL, hold CTRL and then press the following key 
# in the shortcut.  
# 
##########################################################################
#
# 1. Use nano to create a file 
# 
# From exercise 0, you should already have a folder named after your
# NetID in the directory 
# <path_to_repo>/command_line_reu/labyrinth/wooded_lane/meadow/neighborhood
# 
# --> Navigate to your NetID directory. Run `nano <name_of_file>.txt` 
#     where <name_of_file> is whatever you'd like. This will launch nano 
#     while editing your new file.
#
# --> Enter a short message (like 'hello') and then type CTRL+O to save 
#     the file. This is equivalent to a 'save as', and will prompt you 
#     to confirm the name of your file. Press ENTER to confirm, and then
#     CTRL+X to exit nano. 
#
# --> Run `cat <name_of_file>.txt` to print the new contents of your new
#     file to the terminal. 
#
# --> Run `ls -la` and see that the last edited time of your new file is 
#     very recent. 
#
##########################################################################
#
# 2. Use nano to edit your file 
# 
# Note: you should still be in the directory:
# <path_to_repo>/command_line_reu/labyrinth/wooded_lane/meadow/neighborhood/<NetID>
# 
# --> Run `nano <name_of_file>.txt to open your file with nano. Use your 
#     arrow keys to navigate to a new line. You may also need to use the 
#     ENTER key to start a new line. Type the sentence:
#     'peter piper picked a peck of pickled peppers'
#
# --> Save the file by typing CTRL+S. Exit nano by typing CTRL+X. Print
#     the contents of your file to the terminal by running 
#     `cat <name_of_file>.txt`. 
#
# --> Delete a word. Then, undo the action using ALT+U. For Mac users it
#     will be ESC+U (tap, don't hold ESC). Save the file with CTRL+S and 
#     exit with CTRL+X
#
# --> Duplicate/copy and paste the line 'peter piper picked a peck of 
#     pickeled peppers' by navigating to the line, 
#
##########################################################################
#
# 3. Search for a word or phrase in your file
# 
#