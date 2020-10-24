# git-cabinet

Error: `fatal: Could not read from remote repository.`

Fix:
```
eval `ssh-agent -s`
ssh-add ~/.ssh/id_rsa
```
