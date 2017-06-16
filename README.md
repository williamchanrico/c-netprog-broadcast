# c-netprog-broadcast
Broadcast network programming example in C

## Preview
![screenshot](screenshot.png?raw=true "Screenshot")

## Usage
### Broadcast
```
$ gcc broadcast-ipv4.c -o broadcast
$ ./broadcast
usage: ./broadcast <bcast_addr> <bcast_port>
```
### Listener
```
$ gcc listen-broadcast-ipv4.c -o listen
$ ./client
usage: ./listen <bcast_port>
```
### Used Compiler
```
$ gcc --version
gcc (GCC) 6.3.1 20170306
Copyright (C) 2016 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```
