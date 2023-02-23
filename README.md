# Introduction to SSH keys

An SSH key is an access credential in the SSH protocol. Its function is similar to that of user names and passwords, but the keys are primarily ised for automated processes and for implementimg single sign-on by system administrators and power users.

## Important commands
`ssh-keygen -t <type> -b <bytes> -C "<owner>"` - Creates an SSH keypair, one public and one privates

```
eval `ssh-agent -s`
```
note that " ` " is not single quotes!

`ssh -T git@github.com` - Checks if our terminal is connected to GitHub, useful to verify that we can still push content to github

`git remote add origin <https or ssh link>`


