## Git Cheatsheet
###Text based way of talking with my computer!
```bash

cd    # Change the current working directory  (cd byitself... takes to home directory)
      ##   ..  refers to parent directory
      ##    . refers to THIS directory
      ##    ~ refers to home
pwd   # Print working directory
mkdir  # Creates new directory
touch  # Makes a file
ls  # List... show files/directories inside the working directory
mv  # Move  (or rename)
    #  Same as cd: we can use .. and . to reference directories
rm  # Remove     -r flag for recurrsive... needed for removing directories
cp  # Copy

```

## Your Everyday Git Workflow!
Follow in this order every time you want to make a change and push it live!
- `git add .`
- `git commit -m "my witty message here"`
- `git pull origin master`
- `git push origin master`
