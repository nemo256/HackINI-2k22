# Diff

Challenge description:
linux/diff

![Diff](diff.png)

This challenge is easy, especially for linux geeks.

## Step 1
- Accessing the provided link and printing the list of files using ls:

![Step 1a](step-1a.png)

- We can see flag.txt but it we only have permission to run diff using ctf-cracked user as it is shown here:

![Step 1b](step-1b.png)

## Step 2
- Now we run the diff command on flag and any file that has read permissions using the ctf-cracked user:

![Step 2](step-2.png)

- Now, the flag is printed like this:

```
shellmates{You_ma$tered_th3_t00L}
```
