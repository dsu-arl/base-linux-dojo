In this challenge you will learn how to change file permissions on a Linux system.
The `chmod` command is a Linux command for changing user and group permissions for files on the system.
For example, to make a file called "myfile.txt" *writable* for the current user, run the following command:
```
chmod u+w myfile.txt
```

In this command, the `u` represents "user" and the `+w` says to "add write permissions".

> **_NOTE:_** If the `u` is not specified, it is assumed that you are adding the permission to the user, so you can simply type `chmod +w myfile.txt`.

Run `/challenge/solve` to get further instructions.
