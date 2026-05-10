# Assignment Documentation

## Question 1
![alt text](<Question 1.png>)

Create a new folder for your project
```
mkdir folder-name
```

Initialize a Git repository
```
git init
```

Check the current Git status
```
git status
```

Stage the file
```
git add file-name
```

Commit with a meaningful message
```
git commit -m "commit message here"
```

Add the remote (origin) to your local repo
```
git remote add origin repo-url
```

Verify the remote configuration
```
git remote -v
```

Push your code to the remote repository
```
git push -u origin master
```

## Question 2
![alt text](<Question 2.png>)

Check what changes are made before staging
```
git status
```

View differences in the file
```
git diff
```

Stage only specific changes (if possible)
```
git add file-name
```

Commit with a clear message
```
git commit -m "commit message"
```

Stage all changes
```
git add .
```

Commit again
```
git commit -m "commit message"
```

View full commit history
```
git log
```

View compact (one-line) history
```
git log --oneline
```

## Question 3
![alt text](<Question 3.png>)

![alt text](<Question 3 Force Delete.png>)

Create a new branch (e.g., feature-update)
```
git branch branch-name
```

Switch to the new branch
```
git switch branch-name
```

Stage and commit the changes
```
git add file-name
git commit -m "commit message"
```

Switch back to the main branch
```
git switch master
```

Merge the feature branch into main
```
git merge branch-name
```

Delete the branch safely
```
git branch -d branch-name
```

Try force deleting a branch (create a dummy branch for this)
```
git branch -D branch-name
```

## Question 4
![alt text](<Question 4 Part 1.png>)

![alt text](<Question 4 Part 2.png>)

Stash the changes (include untracked files)
```
git stash -u
```

Check the stash list
```
git stash list
```

Apply the stashed changes back
```
git stash pop
```

Commit the changes
```
git add .
git commit -m "commit message"
```

Make another commit with incorrect code
```
git add .
git commit -m "commit message"
```

Undo the last commit using reset
```
git reset commit-id
```

Make another commit
```
git add .
git commit -m "commit message"
```

Undo a commit using revert (create a new reversing commit)
```
git revert commit-id
```

Verify the commit history
```
git log
```