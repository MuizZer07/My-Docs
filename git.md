
### - add all changes in the directory
```
$ git add .
```

### - local commit
```
$ git commit -m "commit message"
```
### - push to remote branch
```
$ git push
```

### - set user email
```
$ git config --global user.email "muizxzer07@gmail.com"
```

### - set username
```
$ git config --global user.name "Muiz Ahmed Khan"
```

### - store git credentials
```
$ git config --global credential.helper store
```

### - initiate git-flow
```
$ git flow init
```

### - check active branches
```
$ git branch
```

### - checkout a branch
```
$ git checkout branch_name
$ git checkout master
```

### - create a feature branch without git-flow extension
```
$ git checkout develop
$ git merge feature_branch

```

### - create a feature branch with git-flow extension
```
$ git flow feature start feature_branch
// the feature branch will be created as feature/feature_branch

$ git flow release start 0.1.0  
$ git flow hotfix start hotfix_branch

```

### - finish a branch with git-flow extension
```
$ git flow feature finish feature_branch
```
