# Remote

Challenge description:
linux/remote

![Remote](remote.png)

This challenge is easy.

## Steps
- Running the given ssh command will print a GOODBYE message.

![Step 1](step-1.png)

- We can get through this by just passing commands to ssh like this: eg: ssh ... 'command'
- Running ls will find the flag.txt directly.

![Step 2](step-2.png)

- Now, just printing the flag using the cat command.

![Step 3](step-3.png)

- The flag is:
```
shellmates{HOW_DID_U_M4d3_i7_HERE!}
```
