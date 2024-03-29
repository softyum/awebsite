#### softyum wesite

- Getting starte with git

```shell
git remote add softyum git@github.com:softyum/awebsite.git

git config --global user.name "softyum"
git config --global user.email "softyum@github.com"

# Set a new remote
git remote add origin git@github.com:/OWNER/REPOSITORY.git
# Change your remote's URL from SSH to HTTPS with the git remote set-url command.
git remote set-url origin https://github.com/OWNER/REPOSITORY.git

# Verify new remote
git remote -v # v=view
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)
```
