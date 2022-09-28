# git-tutorial

## Squash commit

```
git log --oneline
```
```
// git rebase -i HEAD~N (N = number of commits) 
git rebase -i HEAD~3
```
```
click 'i' to update
// keep the first 'pick', update the 2nd 'pick' onwards to 's'
click 'esc'
:wq
```
```
# update commit message
// delete commit message or add '#' to the front of the message
// commit A => #commit A
click 'esc'
:wq
```
```
git log --oneline
```
```
git push --force
```