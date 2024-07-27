# Description

Can you find the flag in [file](strings) without running it?

# KEY POINTS:
grep command:
Grep is a useful command to search for matching patterns in a file.
strings command:
Tool that searches through binary data to find and display sequences of printable characters

The command Syntax:
`grep [options] pattern [files]` <br>
[options]: These are command-line flags that modify the behavior of grep. 
[pattern]: This is the regular expression you want to search for.
[file]: This is the name of the file(s) you want to search within. You can specify multiple files for simultaneous searching.

`strings filename`

 # Solution 
 `strings strings | grep picoCTF`

FLAG:`picoCTF{5tRIng5_1T_7f766a23}`

