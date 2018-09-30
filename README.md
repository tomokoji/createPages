### createPages ###

# Description
  This script is to create a new Pages file on Mac.

  Pages is not a single file but a zip file, and touch command cannot be 
  used for Pages on Terminal. To create a new file, a user usually need to 
  open a new file from the application and specify the location to save it.

  It is easier to create a new file to an arbitrarily directory by command
  line on Terminal. 

# Usage
  This script requires 2 arguments.
  $ createPages <file_path> <file_name>
  
  file_path: The path of a directory where you want to add a new Pages file.
             It should be relative and end with '/' (e.g. Users/Hoge/).
  file_name: The name of a new Pages file.
             It should NOT include an extention '.pages'.

# Install
  There a two ways to use this script.
  (1) Save the script file to any directory and run as ./createPages
  (2) Save the script file and add its path to $PATH. This can be done 
      using addNewCmd.

# Author
  tomokoji

# Date
  30 September 2018
