Know of little and big endian?
Source
nc titan.picoctf.net 60590

# Description

Know of little and big endian?
Source
nc titan.picoctf.net 60590

# KEY POINTS

=> Endianness ensures that bytes in computer memory are read in a specific order.
=> Big-endian (BE): Stores the most significant byte (the “big end”) first. This means that the first byte (at the lowest memory address) is the largest, which makes the most sense to people who read left to right.
=> Little-endian (LE): Stores the least significant byte (the “little end”) first. This means that the first byte (at the lowest memory address) is the smallest, which makes the most sense to people who read right to left.


# Solution
The source file in challenge is a file named "flag.c",it is a program to find the endianness of word.
 `nc titan.picoctf.net 60590`
Here you will have a word:
eg:'vmgzq'
Using *[Cyberchef](https://gchq.github.io/CyberChef/) convert word to its hex value 
eg: 76 6d 67 7a 71 This is the bigEndian representation of the word.
For getting the  littleEndian representation rearrange it from right to left taking two values at a time.
eg: 71 7a 67 6d 76

Submit the answer without spaces.
FLAG:`picoCTF{3ndi4n_sw4p_su33ess_817b7cfe}`
