# Question
Can you break into this super secure portal? https://jupiter.challenges.picoctf.org/problem/56816/ (link) or http://jupiter.challenges.picoctf.org:56816

# Solution
So for this challenge were first introduced with a sd1 file, so I decided to use an sd1 file viewer such as https://filext.com/file-extension/SD1, and through It showed me all the text I need, than I tried searching for picoCTF, nothing came up, so I searched for a curly bracket and this came up:

![alt text](https://github.com/MohammedAl-Rasheed/picoCTF_Solutions/blob/main/Forensics/Images/Sd1.png?raw=true)

From that point I noticed that the picoCTF was on the end of the line, so I assumed it was inversed thus I went to https://cryptii.com/ to reverse the text and I ended up with:

picoCTF{b3_5t111_mL|_<3_cfeb7391} 
