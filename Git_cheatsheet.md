## Git Cheatsheet

###GIT
- Version Control Software

###GITHUB
- Social network... that uses git...

---

```bash

git status  # "What's going on with git right now?"
git add . # Stages all changes
git add fileIChanges.js # Stage specific changes
git commit -m "Feature I accomplished"# Save a version of files
git log # See the past... of this repository
git push [*remote*] [*branch*] # Send this repository with another computer
git push origin master # Send this repository with another computer
        # origin is a NAME for a remote location
        # master is a BRANCH of the repository
git pull [*remote*] [*branch*] # Retrieve a repository from another computer
git pull upstream master # Retrieve a repository from another computer
        # upstream is a NAME for a remote location
        # master is a BRANCH of the repository  

```

## Your Everyday Git Workflow!
Follow in this order every time you want to make a change and push it live!
- `git add .`
- `git commit -m "my witty message here"`
- `git pull origin master`
- `git push origin master`
