<br>#This is the Readme.md file#</br>

This file is to give a brief overview of what the repo is about.
I have created so many repos in the past but this one will always be special. Thanks to the tutor/youtuber Nick White.
He made it so simple that I didn't find Git and Github so overwhelming
I think it was a necessary step to learn fundamentals first but he teacher like a 5yold which is so important.

I am going to put some basic commands that he taught which I think are quintessential in learning GIT.

He taught 

1) Made me download GITSCM as it wasn't on my computer
2) Create a Repo on machine                                                      ||  mkdir gitVideo
3) Use command line using MinTTY
4) Create files to the repo using touch command                                  ||  touch index.html demo.py or touch <filename> for single
5) Initialize the repo with GIT                                                  ||  git init
6) Add files to git using                                                        ||  for all files git add. or single file git add <filename>         
7) Commit those changes                                                          ||  git commit -m 'message'
8) Make changes by deleting and adding new files and re-commiting those changes  ||  rm index.html | commit -m 'removed html file'
9) Config work with email and name                                               ||  git config --global user.email "swapnilamundra1811@gmail.com"  | git config --global user.name "Swapnila Mundra" | To see list                                                                                       git config --list
10) Put the folder created on to GitHub                                          ||  git remote add origin https://github.com/swapnilamundra/gitVideo.git
11) Push to the website                                                          ||  git push -u origin master
12) Create branch on GIT                                                         ||  git checkout -b new-branch (to create new branch) | git branch (to see all branches)
13) To Switch to a branch or cancel creating a new one                           ||  git switch -  | git switch -master | git switch -new-branch
14) Push the branch to GitHub                                                    ||  git push origin new-branch
15) Pull changes from GitHub that you don't have on your computer                ||  git pull origin master
16) To See all previous changes saved                                            ||  git log
17) Travel back to old commit                                                    ||  git checkout <hashvalue of commit>
18) To track status of changes                                                   ||  git status
19) Clone a repo                                                                 || git clone https://github.com/swapnilamundra/gitVideo.git
20) to see the contents of a folder || ls 
to see hidden files and folders ls -a or ls -force (when las -a doesn't work)
21) Change directory/Exit directory            ||  cd  | cd ..
22) Remove directory || rmdir <directory name>
23) To rename a branch || git branch -M main
24) To know current branch || git branch --show current
25) To verify origin || git remote -v 
26) To delete a branch || git branch -d <branchname>
27) To create a new branch  || git checkout -b <branchname>
28) To Switch || git checkout <branchname>

git push -u origin main 
-u indicates to set upstream, meaning if you know for long term you are going to be working in the same project. then set -u and from next time just use => git push

29) To Check differences in two branches || git diff <tobranchname>
30) Merging with command line(without creating pull request on GITHUB) || git merge <tobranchname>
31) Resolving merge conflicts
    Accept Current Change => Keep changes of the current branch you're working in 
    Accept Incoming change => Keep branch2
    Accept Both => Keep both
    Compare Changes
32) Undoing changes
    Before Staging meaning add . || git restore index.html
    After Commit || git reset HEAD~1 (goes back to one commit)
                || use git restore index.html once again
         To remove only from GITHUB || git reset <commit hash value>
         To remove from VS Code as well  || git reset --hard <commit hash value>


33) To see logs in reverse meaning latest first || git log --reverse

34) FORK
    To copy someone else's repository and use it as a rough copy

    creates a new repo with same code and same visibilty settings

    To make changes to someone else's code or make code contributions

    Can be done from GITHIUB forking only master or all branches
    And later can create PR on the original repo