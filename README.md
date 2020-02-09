# My app
This is my first git

## basic git command
initiate under a folder
```
git init
```
create file and dir
```
touch <filename>
mkdir <dirname>
```
show status
```
git status
```
add file to git
```
git add <file>
git add README.md
git add .type
git add .
```
commit it
```
git commit
git commit -m 'comments'
```
link ur github and push/pull it, add -f will force push
```
git remote
git remote add origin http...
git push -u origin master
git push -u origin master -f
git push
git pull
```
after u change something
```
git add <file>
git commit -m 'comments'
git push
```
put the name of the file u wannna ignore
```
touch .gitignore
```
see log and reset
```
git log
git log --pretty=oneline
git reset --hard HEAD~<3>
git reset --hard <commit ID>
```
branches
```
git checkout master
git merge login
```
