









1. Download and install git from  [git-scm](https://git-scm.com/)
2. Check git version

```bash
git --version
```

3. Let Git know who you are

```bash
git config --global user.name "your name"
git config --gloabal user.email "your email"


4. Check the status of files/project
```bash
git status


# the short way
git status  --short

# ?? - Untracked files
# A - Files added to stage
# M - Modified files
# D - Deleted files
```

5. Add a file to the staging enviroment

```
git add <"filename">
# or 
git add .
```