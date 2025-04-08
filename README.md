# editpath
editpath command for editing the $PATH environment variable using the .bashrc file


## setup

1. extract the archive "editpath.zip" (anywhere should do)
 
2. open terminal in the same place you extracted editpath.zip and run "setup.bash" from terminal
   
3. confirm the given directory is your home directory
   
4. wait for setup to finish
   
5. restart terminal and "editpath" should be a valid command
    


## usage

-a (argument)  # adds a string to the list of custom $PATH additions

-d (argument)  # removes a string from the list of custom $PATH additions

-c  # prints contents of the list of custom $PATH additons

-u  # update .bashrc with values from the list of custom $PATH additions

-r  # reset command data (use if broken)
