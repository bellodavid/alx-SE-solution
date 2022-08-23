Warning: Don't copy and paste codes on your terminal, you could be pernalized for that.

## Task 1: Repo-session
    cd alx-pre_course (enter)
    mkdir 0x01-git (enter)
    cd 0x01-git (enter)
    echo “my second commit”>README.md (enter)
    cd .. (enter)
    git add . (enter)
    git commit -m 'My second commit' (enter)
    git push origin main (enter)

    Check your code

## Task 2: Coding fury road
    cd 0x01-git (enter)
    mkdir bash (enter)
    mkdir c (enter)
    mkdir js (enter)
    ls (enter) – this to check if the directories have been created

 
    touch c/c_is_fun.c (enter)
    touch js/main.js (enter)
    touch js/index.js (enter)
    cd c (enter)
    ls (enter)
    cd .. (enter)

    
    cd bash (enter)
    echo ‘#!/bin/bash’ >alx (enter)
    echo “ALX” >>alx (enter)

    echo ‘#!/bin/bash’>school (enter)
    echo “School”>>school (enter)
    cd .. (enter) 
    git add . (enter)

    git commit -m 'Starting to code today, so cool' (enter)
    git push (enter)

    Check your code

## Task 3: Collaboration is the base of a company
    git checkout -b update_script (enter)
    cd bash
    touch 98 (enter)

    echo ‘#!/bin/bash’ >alx (enter)
    echo “ALX School” >>alx (enter)

    echo ‘#!/bin/bash’>school (enter)
    echo “The school is open!”>>school (enter)

    cd .. (enter)
    git add . (enter)
    git commit -m “My personal work” (enter)

    git push --set-upstream origin update_script (enter) – to push the branch to the main)

    git checkout main/master (enter)
 
    cd bash (enter)
    echo ‘#!/bin/bash’ >alx (enter)
    echo “ALX School is so cool!” >>alx (enter)

    cd .. (enter)
    rm -rf js (enter)

    git add . (enter)
    git commit -m 'Hot fix'
 
    git push

    Check your code

## Task 4: Collaboration: be up to date
    Go to github.com, enter your alx-pre_course Repository
    Double tap on 0x01-git

    Click on the README.md file below and click on the edit button. Change the content and commit it

    Get all changes of the main branch locally (i.e. your README.md file will be updated)
    Go to git bash, use the command

    git pull (enter)
 
    Create a new file up_to_date at the root of your directory and in it, write the git command line used
    echo “git pull”> up_to_date  (enter)

    Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin
    git status (enter) to check the status of your work

    git add . (enter)

    git status (enter) to check the status of your work if the previous works has been added.

    git commit -m “How to be up to date in git” (enter)

    git push

    Check your code