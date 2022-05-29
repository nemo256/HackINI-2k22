# Diff

Challenge description:
linux/diff

![Diff](diff.png)

This challenge is easy, especially for linux geeks.

## Steps
- Accessing the provided link and printing the list of files using ls:

![Step 1](step-1.png)

- We can see flag.txt but it we only have permission to run diff using ctf-cracked user as it is shown here:

![Step 2](step-2.png)

- Now we run the diff command on flag and any file that has read permissions using the ctf-cracked user:

![Step 3](step-3.png)

- Now, the flag is printed like this:

```
shellmates{You_ma$tered_th3_t00L}
```
