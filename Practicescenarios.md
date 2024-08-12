# Scenario 1
[You have an existing file in your computer, you want to integrate git and upload to github.]

**solution**
```bash
git init --> git add . --> git commit -m"message" --> create a remote repo and copy repo url -->git remote add origin <url> --> git push origin  main --set-upstream -->git push
```
---
# Scenario 2
[create a new project which should be pushed to github]

**solution**
:There are two ways of dealing with this problem:
**soln-1(Create a local repo for the proj and push to github)**
```bash
create project -->git init --> git add . --> git commit -m"message" --> create a remote repo and copy repo url -->git remote add origin <url> --> git push origin main --set-upstream -->git push
```
**soln-2(Create a remtoe repo for the proj and clone on local machine)**
```bash
create a remote repo and copy repo url --> git clone <url>--> create code for project--> git push origin main --set-upstream -->git push
```