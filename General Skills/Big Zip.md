# Description

Unzip this archive and find the flag.
Download zip file

# KEY POINTS:
grep command:
Grep is a useful command to search for matching patterns in a file.

The command Syntax:
`grep [options] pattern [files]` <br>
[options]: These are command-line flags that modify the behavior of grep. 
[pattern]: This is the regular expression you want to search for.
[file]: This is the name of the file(s) you want to search within. You can specify multiple files for simultaneous searching.

 # Solution 
 `unzip big-zip-files.zip`
 `cd big-zip-files/`
 `grep -r "pico"`

FLAG:`picoCTF{gr3p_15_m4g1c_ef8790dc}`

