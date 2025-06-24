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
#     pickeled peppers' by navigating to the line, typing ALT+6, 
#     navigating to a new line, then typing CTRL+U. Save and quit by
#     typing CTRL+S and CTRL+X.
#     Alternatively, you can cut and paste the same line by navigating to
#     the line, typing CTRL+K, then typing CTRL+U. You can type CTRL+U 
#     repetatively to paste the line multiple times. After trying this
#     out, save the file with CTRL+S. 
#
# --> You can also copy-paste things into nano (from outside sources 
#     like the internet) by using the usual CTRL+C and CTRL+V 
#     (CMD+C and CMD+V on Mac). Try this in your file using your favorite
#     ASCII art from this website: https://www.asciiart.eu/ .
#
# --> After pasting your ASCII art from the internet, duplicate it in nano
#     by cutting (CTRL+K) all of the lines of the art, then pasting 
#     (CTRL+U) the contents of your cutbuffer (clipboard). For example, 
#     if my art is 5 lines long, I will CTRL+K 5 times in a row and then 
#     CTRL+U once. 
#
##########################################################################
#
# 3. Search for a word or phrase in your file
# 
# Note: you should still be in the directory:
# <path_to_repo>/command_line_reu/labyrinth/wooded_lane/meadow/neighborhood/<NetID>
#
# --> In your file, find the word 'peppers' by typing CTRL+W, 'peppers',
#     and ENTER. Find the next occurance(s) of that word by repetatively 
#     typing CTRL+W and ENTER. If you'd like to change the serch term, type
#     CTRL+W, type a new search term, then press ENTER. 
#
# --> Toggle on/off line numbers by typing ALT+N or ALT+# (ESC+# on Mac
#     and tap don't hold ESC). 
#
# --> Test out whatever else you'd like in nano using the provided 
#     shortcuts. 
#
##########################################################################