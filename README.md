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
git log // view particular branch versions only
```

__8. Undos files in the staging area to changes area__
```
git reset file/folder/.
```
__9. Discard changes__
```
git checkout -- file/folder/.
```

__10. View Braches__
- similar to git log.
- Git:
Going back previous version and commit changes results in branching, coming from that version.
- Google Doc:
The committed changes will be a new version rather than branching out.
- Head - active or "current" branch - where you are at.
- Master - aka. main (branch name)

```
git log --all // view all commits/ versions of all branches.
git log --all --graph // shows graph - visualize branching effect (if any)
```

__11. Going back previous version__
- Head will be at previous version - indicates that you are at previous version.
Note: Commit changes when you are at the previous version resulting in branching!

```
git checkout branch-name //e.g., master
git checkout commit_hash  //e.g., 2eaa98a2f672c66eb5c770c3e979d82290e09304
```

__11. Restoring Avoid branching__
- Restore to previous version (copy previous version and paste in current version without going back to previous version and commit new changes that results in branching.) 
Note: Head is not at previous version, still current version.
- commit_hash of version you wish to restore
- which folder/files to be restored?
```
git checkout commit_hash folder/file/.
```