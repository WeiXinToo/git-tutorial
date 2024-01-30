# Git Command - Version Control Tool

__1. Configures username and email__
```git
git config --global user.name "username"
git config --global user.email "email"
```


__2. Initialize git - to start tracking changes__
```
git init 
```

__3. shows files in changes area, files to be commited in the staging area, and other untracked/ new files that not being tracked by git__ 
```
git status
```

__4. Picks changes to go into next commit__
```
git add file/folder/.
```

__5. Creates a commit with a message attached__
```
git commit -m "message"
```

__6. Updates previous commit - where ammend message and include new files__
```
git commit -m "message" --amend
```

__7. Views the commit history__ 
```
git log
```

__8. Undos files in the staging area to changes area__
```
git reset file/folder/.
```
__9. Removes changes__
```
git checkout -- file/folder/.
```