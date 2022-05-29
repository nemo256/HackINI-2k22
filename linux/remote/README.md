# Remote

Challenge description:
linux/remote

![Remote](remote.png)

This challenge is easy.

## Step 1
- Running the given ssh command will print a GOODBYE message.

![Step 1a](step-1a.png)

- We can get through this by just passing commands to ssh like this: eg: ssh ... 'command'
- Running ls will find the flag.txt directly.

![Step 1b](step-1b.png)

- Now, just printing the flag using the cat command.

![Step 1c](step-1c.png)

- The flag is:
```
shellmates{HOW_DID_U_M4d3_i7_HERE!}
```
