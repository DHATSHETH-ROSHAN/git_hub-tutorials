# new-project-

## connect or pull repository to vs code then save it into your system
    git clone http.......

## after creating new file it will be as untracked file in vs code then need copy to git folder in desktop (M)
    git add filename 
## then to git hub local repsitory folder
    git commit -m "message"
## then to git hub
    git push origin main
    origin = http link 
    main  = branch
## create file in git hub
    add file -> new file ->
## then how to bring the file into our system
    git pull origin main

## now creating folder in our pc
   create folder-> create file ->save
## then make it as git repository (U)
    git init
## if created more file in folder now update all using single command 
    git add .
## now we neeed to commit them 
  git commit -m "message"
## now create repository in the git hub with the name 
    add new -> new repository(then copy the link in it)
## now we need to save them to git hub
    git remote add origin http link
## now push to the folder in github
    git push origin master(it was in the name of master as branch name)
## or change the name of branch from master to main
    git branch -m master main  
    or 
    git branch -M main
## now push to folder in github
    git push origin main

## to know how many branch in your repository
    git branch -a





## git definitions
    U - untracked
    M - modified
    R - removed
    A - added
    C - committed
    D - deleted
## git commands
    git init
    git add .
    git commit -m "message"
    git remote add origin http link
    git branch -m master main
    git branch -M main
    git push origin main
    git pull origin main
    git status
    git log
## git commands with explanation
    git init - initialize the git repository
    git add . - add all the files in the current directory to the staging area
    git commit -m "message" - commit the files in the staging area with a message
    git remote add origin http link - add a remote repository to the local repository
    git branch -m master main - rename the branch from master to main
    git branch -M main - rename the branch from master to main and force the push
    git push origin main - push the changes to the remote repository
    git pull origin main - pull the changes from the remote repository


