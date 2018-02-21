### Git Basics

#### Trainers: Uladzimir Halushka

#### Slides 

http://slides.com/uladzimirhalushka/deck-1

#### Video

https://youtu.be/ankvwnNJFPA

#### Content
- Introduction to Version Control
- The cd command
- .gitconfig file
- Vi editor
- Cloning a repository
- What is "origin" in Git?
- git status
- git add
- git commit
- git push
- git log
- git revert
- workspace - index - local repository - remote repository
- clear command 
- touch command
- git commit -m
- git checkout 
- Branching Strategy
- git merge 
- git fetch
- git pull
- How to resolve merge conflicts in Git
- git stash
- .gitignore
- gh-pages
- Git guidelines

## Git guidelines
In general, the preferred Git workflow is:

1. Create a branch from `master`, check it out, do your work.  
Please, use required branch name from the task. If task name consist of two words, use `-` for separating. For example:  
~~taskName~~, ~~task_name~~, `task-name`

2. Commit changes. Required commit name is `TASK_NAME[/TYPE]: message`.  

| Good commit naming  |Bad commit naming|  
|:--------------------|:----------------|
|`binary-tree/feature: implement traverse method`|  `init commit`   |
|`binary-tree/fix: error in the empty tree`|`fix`|
|`youtube: rename constans`|`чейнджи`|

_After that optionally push your branch up to the remote repository_



## GitHub Pull Request (PR) guidelines

1. PR name should contains **the task name** and probably additional info.
2. Changes **must not contain commented code, unnecessary files, changes from other branches and generated files** like *.bundle.js. Please review your changes before contributing. .editorconfig, .gitignore, etc. can be included.
3. Comments in the PR are good practice.
4. [How to write the perfect Pull Request](https://github.com/blog/1943-how-to-write-the-perfect-pull-request)



## Git cheatsheet  
Git allows a developer to copy a remote subversion repository to a local instance on their workstation, do all their work and commits in that local repository, then push the state of that repository back to a central facility (**github**).  

| Command |Meaning|  
|:--------------------|:----------------|
|`git clone git@github.com:r/r.git`| Get a copy of the central storage facility (the repository)   |
|`git branch first-task`|Create a _local_ branch called "first-task" |
|`git checkout first-task`  |Swith to the first-task branch |
|`git checkout -b first-task`  |Create and swith to the first-task branch |
|`git add index.js`  |Add `index.js` contents to the index.|
|`git add .`  |Add all content from the current folder to the index|
|`git commit index.js`  |Add `index.js` contents to the index|
|`git push origin first-task`  |Push the current state of your `first-task` branch, including all commits, up to github.|
|`git pull`  |Bring your local branch up-to-date with the state of the remote branch on github.|


#### Useful links 
-  https://git-scm.com/book/id/v2/Getting-Started-Git-Basics
- http://alistapart.com/article/the-art-of-the-commit
- https://www.atlassian.com/git/tutorials/merging-vs-rebasing

#### Online courses
- https://www.codeschool.com/courses/try-git
- https://www.codeschool.com/courses/git-real
