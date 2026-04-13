# Level 0

The goal is to log into the game via SSH using the provided credentials.

- Host: bandit.labs.ovethewire.org
- Username: bandit0
- Password: bandit0

SSH (Secure Shell) is a protocol for securely connecting to remote machines over a network.

Using the command:

`ssh -p port user@host`

In which `-p` specifies the port and `user@host` being our user and host, we input the command:

`ssh -p 2220 bandit0@bandit.labs.overthewire.org`

Logged in successfully with password `bandit0`. Moving on to Level 1.
