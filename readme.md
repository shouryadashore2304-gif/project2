the project created by me
to add things in github
# new repository ma daalna hai
    git remote add origin link paste kardo
    then -> ek baar check karlo -> git remote -v
    then -> git branch -M main // apan ne repository ko "main" naam se address kiya hai vs vs code ma
    1)then-> git add .
    2)then-> git commit -m "something msg"
    to simpify 1 and 2 we can directly write = git commit -am "msg"
    then-> git push origin main

# bug
    git pull origin main --rebase (for any difficulty in pushing)

# first 
    git commit -m "updated anuthing"
    //if created a folder
    then git add .
    then git commit -m "updated anything"

    |
    v

    git push -u origin main = means after that we have to type only git push
    so to push code -> git push


# git branches
    git branch (to check branch)
    git branch -M main (to rename branch)
    git checkout <branch name> (to navigate)
    git checkout -b <new branch name> (to create new branch)
    git branch -d <branch name> (to delete branch)
    git push --set-upstream origin <new branch name> (to push new branch code in origin)

# pull    
    git pull origin main.

# staged changes
    git reset <file name>
    git reset

# commited changes (for one commit)
    git reset HEAD~1    

# commited changes (for many commits)
    git reset <commit hash>
    git reset --hard <commit hash> (hata rahe changes screen pe)
    commit hash will be known from commit log = "git log"    