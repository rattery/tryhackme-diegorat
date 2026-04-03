# Level 0

The goal of this level is to log into the game using SSH. The host we need to connect to is `bandit.labs.overthewire.org`, on port `2220`. The username is `bandit0` and the password is `bandit0`.

Once logged in, we must go to the `Level 1` page to find out have to beat `Level 1`.

We will being using the command `ssh` and researching over such command and how to acheive our goal.

### Sources Provided

- `https://en.wikipedia.org/wiki/Secure_Shell`
- `https://itsfoss.com/ssh-to-port/`
- `https://www.wikihow.com/Use-SSH`

#### Wikipedia Source

The Secure Shell Protocol is a cryptographic network protocol for operting network services securely over and unsecured network.

SSH uses public-key cryptography to authenticate the remote computer and allow it to authenticate the user, if necessary.

In the simplest form, both ends of a communication channel use automatically generated public-private key pairs to encrypt a network connection, and then use a password to authenticate the user.

When a public-private key pair is made manually, the authentication is performed when the key pair is created, and a sessionmay then open automaticlly without a password prompt. In this case, the public key is placed on all computers that must be allowed access to the owner of the matching private key, which the owner keeps private. The key is never transferred through network and only verifies that the same public key also matches the private key.

#### ItsFoss Source

Learn how to connect via SSH to a port other than the default 22 and how to change the SSH server port.


When we use `ssh user@IP`, it tries to connect to the default port 22. If the remote server uses some other port for SSH, you should provide the port number.

`ssh -p port_number user@IP`

Lets say we wanted to connect to a remote server with an IP of 64.227.184.93 that accepts SSH connections at port 7770.

`ssh -p 7770 abhishek@64.227.184.93`


