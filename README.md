# shell-script-commands
Compilation of usefull shell script commands

- List most N larger files in a folder

  Example: list 50 most larger files in folder
  
  ```
  du -am PATH_TO_FOLDER | sort -n -r | head -n 50 
  ```
