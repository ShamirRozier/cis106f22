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
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to 
## man
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## mkdir
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## mv
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## tac
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## tail
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## touch
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## tr
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## tree
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to
## vim/nano
* Description:
  * 
* Formula:
  * `head + options + file or files`
* Examples:
  * how to

