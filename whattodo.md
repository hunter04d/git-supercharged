# What is going on

This is a file with a rough description of all of the demos\
You can use this file to practice using git commands\
*(note: there are no demos of the remote commands, however\
 we still encourage you to try some remote commands as well)*

## **first demo**

go to github.com\
_log in_\
show where to add an shh key\
go to the front page\
create new repository

## **./init**

initialize the repository\
and add some files

show the following commands at least:

```bash
$git status
$git commit
$git rm
# and
$git mv
$git status
$git commit -m ""
```

## **./merge vs rebase**

### 2 folders with the same repository

**For the first one** merge all branches into master

**For the second** rebase all branches\
explain the ```--onto``` option\
and ```git branch -f master``` on top of the tree

## **./Tagging**

1. add _annotated_ tag to the first commit
2. tag the tip of some branch (lw tag)
3. delete the branch
4. show that you can still navigate to that branch via the tag
5. delete the tag
6. show that those commits are no longer reachable
7. use the ```git reflog``` to show that the history is never really gone

## **./Merge conflict**

resolve a merge conflict via the editor

```bash
$git add .
$git merge --continue
```

## **./Interactive**

do an interactive rebase of the ```HEAD~3``` with a squash and an amend