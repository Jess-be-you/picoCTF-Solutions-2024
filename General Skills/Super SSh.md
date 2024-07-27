# Description

Using a Secure Shell (SSH) is going to be pretty important.<br>
Can you ssh as ctf-player to titan.picoctf.net at port 63420 to get the flag?<br>

KEY POINTS:<br>
SSH, also known as Secure Shell or Secure Socket Shell, is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.

The command Syntax:
`ssh targetusername@targetwebsite/targetmachineip -p portnumber` <br>
 If asked, accept the fingerprint with "yes"
 You'll also need the password in the task.

 # Solution 
 `ssh ctf-player@titan.picoctf.net -p 63420`

FLAG:`picoCTF{s3cur3_c0nn3ct10n_8306c99d}`

