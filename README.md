# Git-Hub-Problem-Solve

# ! [rejected]        master -> master (fetch first) <br> error: failed to push some refs to "URL"

```
---Approch 1---
git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

---Approach 2---
git remote add origin https://github.com/userName/repoName.git
git push --force origin master

---Approach 3---
git fetch origin master
git pull origin master
git add .
git commit -m 'your commit message'
git push origin master
```
