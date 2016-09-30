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
```

Record changes to the repository

### git add - https://git-scm.com/docs/git-add

```sh
$ git add --all
```

Add file contents to the index

### git push - https://git-scm.com/docs/git-push

```sh
$ git push
$ git push origin work
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
```

Show changes between commits, commit and working tree

### git show - https://git-scm.com/docs/git-show

```sh
$ git show
```

Show various types of objects

### git cat-file - https://git-scm.com/docs/git-cat-file

```sh
$ git git cat-file -p head
$ git cat-file -p 54cacd
$ git cat-file -p 579500
```

Provide content or type and size information for repository objects
