# Installation
For easy install run this command
```bash
cp ~/.bashrc ~/.bashrc.bak ; curl -k -Ss https://raw.githubusercontent.com/HX-Rd/browser-bash-navigation/master/browserrc >> ~/.bashrc ; source ~/.bashrc
```
For manual install you can copy the contents of the browserrc into your .bashrc

## Usage
cd -> pushes into the stack
bb -> change to a previous directory
ff -> change to a directory you where in before you went back with bb
ll -> list the stack contents
gg (number in stack) -> hop to a indicated place in the stack
dcl -> clear the directory stack

## More info
You can read more about the implementation here
https://hx-rd.com/2017/06/09/bash-browser-like-navigation/
