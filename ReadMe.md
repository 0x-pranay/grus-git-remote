 ### initialize git
`git init`


### make some changes

 `create a new file or change existing file`

### add those files to staging
  `git add <fileName>`


### commit those changes
 `git commit -m 'Commit message'`


### create a branch
  `git branch <branch_name>`


### list all the branches

  `git branch`

   or 

  `git branch -a`


### Switch to a new branch
 `git checkout <branch_name>`


### Fetch - dowload latest changes in your local machine
`git fetch origin`


### Pull - Fetches and then merge changes in the branch
`git pull origin master`


### Clone
- mkdir reponame
- cd into that
- git init
- git remote add origin <git-url>
- git pull

### Hard Reset

`git reset --hard HEAD^` -> This will remove last one commit and delete all the changes. 
 Use it with care. 

