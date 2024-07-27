# Description

I accidentally wrote the flag down. Good thing I deleted it!
You download the challenge files here:
challenge.zip

# KEY POINTS:
git version control:
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.Here we have backtrack the commit that we have been deleted so as to get the flag.



 # Solution 
 `unzip challenge.zip`
 `cd drop-in`
 `ls` You will find a message.txt file
 `git init`
 `git log`  
 You can see your past commits with git log. By default, this will show the author, commit ID, time, and description. 
The commit ID will be a long series of letters and numbers. This is based on a 'hash' of your file
`git checkout <commit ID>` use the 1st commit id and cat the message.txt file .Repeat the same for 2nd commmit id and output the message.txt. You will get the flag


FLAG:`picoCTF{s@n1t1z3_7246792d}`

