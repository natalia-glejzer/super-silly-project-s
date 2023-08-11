# super-silly-project-s
## (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧   (｡・//ε//・｡) ♡
A repository that is supposed to help us:
  - develop our fun IT projects;
  - learn how to use git and github.

Feel free to edit the README.md file if you feel like it. Don't be afraid to be silly. 

## How to use github?
Quite long tutorial, but rather informative:
https://www.youtube.com/watch?v=RGOj5yH7evk.
I strongly advise downloading GitHub Desktop (a lot easier to work locally with the code and no need to fool around with the authetication methods).

Here are some commands that I wrote down after watching the tutorial:
### Working with files locally, committing and pushing
  - git status    –> shows all of the files that were updated 
  - git add .    -> while working locally indicate which file you want to track (in this case every signle one of the files) 
  - git add nazwa_pliku.file_extension    -> adding a specific file to track
  - git reset name-of-the-file    -> unstage a file
  - git reset HEAD~1    -> going back with the commits (HEAD - a pointer to the last commit, ~1 - means that we want to go a step futher)
  - git log    -> logs of all the commits (there are commit hashes that we can use in the "git reset" command, if we want to go back to any specific commit)
  - git reset --hard hash-from-the-logs    -> we want to not only unstage the changes but also to remove them completely
  - git commit –m “Title of our commit” -m “Longer descriprion (why the changes were made etc.)”    -> sending the changes but they aren’t live yet 
  - git push origin name-of-the-branch    -> pushing changes to remote repository, push changes live, origin – location of our git repository (If you want to use push command you need to read some more about the SSH keys. If don't want to do that, using GitHub Desktop works just fine for now on. Remember, first you commit, then you push.)
  - git pull origin name-of-the-brnach    -> pull the code from the remote repository into your local "workspace"

### Branches
  -  git branch     -> check a branch you're currently on (the head branch) and see the list of all of branches
  -  git checkout name-of-the-branch    -> switch to another already existing branch
  -  git checkout -b name-of-the-branch    -> create a new branch and switch to it
  -  git diff name-of-the-branch    -> show differences between the branch you're currently on and the other indicated branch (a good practice before merging two branches)
  -  git branch -d name-of-the-branch    -> delete branch

## Inspirations:
  - https://www.codedex.io/projects

## ଘ(✿˵•́ ᴗ •̀˵)
