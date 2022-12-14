# Question 1

## awk
* Description:
  * awk is useful for manipulation of data files, text retrieval and processing,  and  for prototyping and experimenting with algorithms.
* Formula:
  * `awk + options + awk command + file`
* Examples:
    * how to print the first field of a file:
        * awk -F':' '{print $1}' /etc/passwd
    * How to start printing from a different line
        * awk 'NR > 3 {print}' /etc/passwd
    * how to change a field to upper case:
        * awk -F: '{print toupper($1)}'

## cat
* Description:
  * used for seeing the content of a file. Also used for concatinating files
* Formula:
  * `cat + options + file or files to view/concatinate`
* Examples:
  * how to see the content of a file
    * `cat etc/passwd`
  * how to see the content of a file with line numbers:
    * `cat -n etc/passwd`
  * how to see the content of a file with ending line character
    * `cat -E etc/passwd`
## cp
* Description:
  * copy files and directories
* Formula:
  * `cp + options + file or files + destination`
* Examples:
  * how to copy a file
    * `cp file.txt ~/Documents/files/`
  * how to copy a directory
    * `cp ~/Documents/files/ ~/Documents/files2/`
  * how to copy only when the SOURCE file is newer than the destination file or when the destination file is missing
    * `cp -u file.txt ~/Documents/files/`
## cut
* Description:
  * remove sections from each line of files
* Formula:
  * `cut + options + file or files`
* Examples:
  * how to cut only with specific bytes
    * `cut -b 1,2,3 state.txt`
  * how to only cut by character collumn
    * `cut -c 2,5,7 state.txt`
## grep
* Description:
  * grep  searches for PATTERNS in each FILE and prints each line that matches a pattern.
* Formula:
  * `grep + options + pattern + file`
* Examples:
  * how to look for the word pie in a file
    * `grep "pie" ~/Documents/Recipies1.txt`
  * how to look for the word pie in multiple files
    * `grep "pie" ~/Documents/Recipies*`
  * how to look for the word pie without case sensitivity
    * `grep -i "pie" ~/Documents/Recipies.txt`
## head
* Description:
  * output the first part of files
* Formula:
  * `head + options + file or files`
* Examples:
  * how to show the first ten lines in a file
    * `head example.txt`
  * how to show the first 5 lines in a file
    * `head -n 5 example.txt`
  * how to show the first 5 characters in a file
    * `head -c 5 example.txt`
## ls
* Description: 
  * Lists information about files and directories
* Formula:
  * `ls + options + file or files/directories`
* Examples:
  * how to long list
    * `ls  -l  ~/Documents/`
  * how to view hidden files
    * `ls -a ~/Documents/`
  * how to long list as human readable
    * `ls -lh ~/Documents/`
## man
* Description:
  *  an interface to the system reference manuals
* Formula:
  * `man + options + command`
* Examples:
  * how to view a commands manual
    * `man ls`
  * how to view section 2 of the manual
    * `man 2 ls`
  * how to instantly find the command
    * `man -f ls`
## mkdir
* Description: make directories
  * make directories
* Formula:
  * `mkdir + options + dirctory or directories`
* Examples:
  * how to make a directory
    * `mkdir ~/Documents/examplefolder/`
  * how to make also make parent directories
    * `mkdir -p ~/Documents/examplefolder/examplefolder2`
  * displays a message
    * `mkdir -v ~/Documents/examplefolder/`
## mv
* Description:
  * moves and renames files
* Formula:
  * `mv + options + file or files + destination`
* Examples:
  * how to move a file
    * `mv example.txt ~/Documents/(example.txt?)`
  * how to rename a file
    * `mv example.txt ~/Documents/(rename.txt?)`
  * aks for confirmation
    * `mv -i example.txt ~/Documents/(example.txt?)`
## tac
* Description:
  * concatenate and print files in reverse
* Formula:
  * `tac + options + file or files`
* Examples:
  * how to  print a file in reverse
    * `tac example.txt`
  * seperator
    * `tac -b concat.txt tacexample.txt`
  * no seperator
    * `tac -r concat.txt tacexample.txt`
## tail
* Description:
  * output the last part of files
* Formula:
  * `tail + options + file or files`
* Examples:
  * how to print the last 10 lines of a file
    * `tail example.txt`
  * how to print the last 5 lines of a file
    * `tail -n 5 example.txt`
  * how to print the last 5 characters of a file
    * `tail -c 5 example.txt`
## touch
* Description:
  * make a file
* Formula:
  * `touch + options + file or files`
* Examples:
  * how to make a file
    * `touch ~/Documents/example.txt`
  * how to change access time
    * `touch -a fileName`
  * how to update modification time
    * `touch -c fileName`
## tr
* Description:
  * translating or deleting characters.
* Formula:
  * `tr [OPTION] SET1 [SET2]`
* Examples:
  * how to translate lowercase to uppercase
    * `greekfile | tr [a-z] [A-Z]`
  * How to translate white-space characters to tabs
    * `echo "Welcome To GeeksforGeeks" | tr [:space:] "\t"`
  * How to translate braces into parenthesis
    * `tr "{}" "()" <greekfile >newfile.txt`
## tree
* Description:
  * visually display parenthood
* Formula:
  * `tree + options + directory or directories`
* Examples:
  * how to show parenthood
    * `tree ~/Documents/`
  * list with a pattern
    *  `tree -P sample*`
  * list with perissions
    * `tree -p ./GFG`
## vim/nano
* Description:
  *  text editoer
* Formula:
  * `vim/nano + options + file or files`
* Examples:
  * vim
    * more powerful/harder to learn
  * nano
    * less powerful/easier to learn
  


