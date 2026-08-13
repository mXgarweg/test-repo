# My Git & GitHub learning

This repository is created for my Git and GitHub learning and training.
Also this README.md contains my personal notes. 

## Basic workflow

A basic workflow for creating a repository and committing:

`git init`

`git remote add origin REPO_URL`

`git branch -M main`

---

`git diff`
`git diff FILENAME`

---

`git add .`
`git add FILENAME`
`git add *.FILETYPE`

---

`git commit -m 'MESSAGE'`
*Why imperative verb for commit message?*
Think like: 'If my commit is applied, it will ...' [e.g; add/update file xy, fix line in file xy]

`git status`

`git push -u origin main`

---

`git rm FILENAME`

---
## branches

`git branch` (show branches)
`git branch -v` (show branches with their last commit)
`git branch FEATURE-XY` (create branch for production server, pre-production server, development server, single feature, etc.)


### merging

`git branch`
`git checkout FEATURE-XY` (switch to branch FEATURE-XY)

***work in branch FEATURE-XY, e.g. create file feature-xy.html***

`git add feature-xy.html`
`git commit -m "add feature-xy.html file"`
(-) git push
(+) git push -u origin FEATURE-XY

`git checkout main`
`git merge FEATURE-XY`

`git status`
`git push`


---
## Markdown

Escape character: \

Line Break: `<br>`

Unordered/ordered list:

+ a
+ b
+ c

1. First
2. Second

**bold** 
*italic*

---
Code: `

```html
<html>test<html>
```
