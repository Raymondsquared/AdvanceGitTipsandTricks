# AdvanceGitTipsandTricks
Advance Git Tips and Tricks

### git clone - https://git-scm.com/docs/git-clone

```sh
$ git clone https://github.com/Raymondsquared/AdvanceGitTipsandTricks.git
```

Clone a repository into a new directory

### git status - https://git-scm.com/docs/git-status

```sh
$ git status
```

Show the working tree status

### git commit - https://git-scm.com/docs/git-commit

```sh
$ git commit -a -m "Put your message here"
$ git commit --amend
```

Record changes to the repository

### git add - https://git-scm.com/docs/git-add

```sh
$ git add --all
$ git add .
```

Add file contents to the index

### git push - https://git-scm.com/docs/git-push

```sh
$ git push
$ git push origin work
$ git push origin --delete work
$ git push -u origin experiment
```

Update remote refs along with associated objects

### git branch - https://git-scm.com/docs/git-branch

```sh
$ git branch
$ git branch work
$ git branch -d work
```

List, create, or delete branches

### git checkout - https://git-scm.com/docs/git-checkout

```sh
$ git checkout work
```

Switch branches or restore working tree files

### git merge - https://git-scm.com/docs/git-merge

```sh
$ git merge work
$ git merge master
```

Join two or more development histories together

### git log - https://git-scm.com/docs/git-log

```sh
$ git log
```

Show commit logs

### git diff - https://git-scm.com/docs/git-diff

```sh
$ git diff
$ git diff head~1..head --stat
$ git diff head~2:README.md..head:README.md
$ git diff --staged
```

Show changes between commits, commit and working tree

### git show - https://git-scm.com/docs/git-show

```sh
$ git show
```

Show various types of objects

### git cat-file - https://git-scm.com/docs/git-cat-file

```sh
$ git cat-file -p head
$ git cat-file -p 54cacd
$ git cat-file -p 579500
```

Provide content or type and size information for repository objects

### git add - https://git-scm.com/docs/git-add

```sh
$ git add README.md
```

Add file contents to the index

### git reset - https://git-scm.com/docs/git-reset

```sh
$ git reset HEAD
$ git reset --hard HEAD~1
$ git reset --hard origin/master
```

Reset current HEAD to the specified state

### git rebase - https://git-scm.com/docs/git-rebase

```sh
$ git rebase HEAD
$ git rebase -i HEAD~4
$ git rebase --continue
$ git rebase --abort
```

Reapply commits on top of another base tip

### git stash - https://git-scm.com/docs/git-stash

```sh
$ git stash save "WIP"
$ git stash list
$ git stash save apply
$ git stash save drop
$ git stash save pop
```

Stash the changes in a dirty working directory away
