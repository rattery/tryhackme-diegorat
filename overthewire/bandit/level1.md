# Level 1

The goal is to find a fill called `readme` in the home directory to gain acess to credentials to progress to level2 by logging into bandit1 using SSH.

Using `cd`, I found the home directory and made sure the `readme` file was there using `ls`. I used the command `cat readme` to display the text in the file on the terminal and recieve the password.

To connect to the room, I typed the command:

`ssh -p 2220 bandit1@bandit.labs.overthewire.org`

Logged in successfully with the password: `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`. Moving on to Level 2.
