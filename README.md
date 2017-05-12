IMPORTANT: Outputs correctly only for git of version 1.8.3 and later!!!

Lists current git directory in pretty human readable format.
Shows file name, when it was changed, abbreviated commit hash, author and commit message. Just like github does, but a little bit better!
This information is really useful when you're getting acquainted with some repository that is unfamiliar to you. 

This is a modification of a script that was provided in one of the answers to this stackoverflow.com question:
http://stackoverflow.com/questions/17359370/git-show-last-commit-date-and-message-for-each-file-in-directory-like-github

# Ubuntu:
I have the following alias in my .bashrc:
```shell
alias gitls="bash ~/scripts/gitls"
```
Tested:
- in gnome-terminal on Ubuntu 14.10
- in gnome-terminal on Ubuntu 12.04.5 LTS (with upgraded git version 2.6.3!)
- in urxvt on Ubuntu 14.04
- in roxterm on Ubuntu 14.04
- in xterm on Ubuntu 14.04

# MacOs:
I have the following alias in my .bash_profile:
```shell
alias gitls="bash ~/scripts/gitls.sh"
```

Tested:
- in terminal on macOS Sierra 10.12.4
- in iTerm on macOS Sierra 10.12.4

![Pretty git ls-tree](/gitls.png?raw=true "Example output")
