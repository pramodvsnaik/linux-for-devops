### 01 - COMMAND SYNTAX

Before dwelling into the various Linux commands it is helpful to understand the Linux command syntax, as it will free you of memorising commands (at least for beginners) and applying them well in your scenarios.

```
COMMAND-NAME [OPTION]...... [ARGUMENT]..

```

COMMAND-NAME : As the name implies, it is the name of the command. example: `ls`, `cd` and so on.

[OPTION] : OPTION is used to specify the behaviour of the command. <br/> 
                   - OPTION always sart with hyphen. example `-la`<br/> 
                   - Here [] indicate that it is optional <br/> 
                   - Multiple OPTIONS can be grouped together as -la <br/> 
                    *For example*: suppose you want to list all file, so as you know for list listing files/directories you will use `ls` , and while listing if you alos have a need to know the permissions listed items, you will specify the OPTIONS, like `ls -la`

[ARGUMENT] : ARGUMENT is the input to the command, that is, command operates on ARGUMENT passed to it inorder to generate result.<br/> 
            - Here [] indicate that it is optional <br/> 
            - Multiple ARGUMENTS can be passed seperated by `space` for a single command. 
