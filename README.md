# git-delete
Deleting the files using git command

* If not done git add .
```bash
git clean -fdn
```
This will show you the files that are to be removed

Now to remove these files
```bash
git clean -fd
```
* If done git add . and not git commit.
```bash
git reset
```

* If done both
```bash
git reset HEAD~1
```
* for hard reset
```bash
git reset --hard HEAD~1
```
* If pushed too then 
find the commit has using
```bash
git log
```
```bash
git revert <commit-hash>
```
```bash
git push
```
