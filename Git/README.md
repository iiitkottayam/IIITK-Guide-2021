# Git

Git is the most commonly used version control system. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.


***Version Control System:*** Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time


### Installing: 
[Git Installation](https://git-scm.com/)



### Create repository:

Turn an existing directory into a git repository
```
git init
```

Clone (download) a repository that already exists on
GitHub, including all of the files, branches, and commits
```
git clone [url]
```



### Branching

Create a new branch
```
git branch [branch-name]
```

Switches to the specified branch
```
git checkout [branch-name]
```

Combines the specified branch’s history into the current branch.
```
git merge [branch]
```

Deleting branch (Caution!!!)
```
git branch -d [branch-name]
```



### Making Changes

Lists version history for the current branch
```
git log
```

Show difference between two branches
```
git diff [first branch]...[second-branch]
```

Snapshot of file in preparation for versioning
```
git add [file]
```

Record the snapshots permanently in version history
```
git commit -m "[commiting message]"
```

Uploads all local branch commits to GitHub
```
git push
```

If our Github is updated but not local repo
```
git pull
```


### .gitgnore file
Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named .gitignore .


