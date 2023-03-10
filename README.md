# Git Commands

## Create repositories
```bash
$ git init
```

```bash
$ git clone [url]
```

## Configure tooling

```bash
$ git config --global user.name "[name]"
```

```bash
$ git config --global user.email "[email address]"`
```

## Branches

```bash
$ git branch [branch-name]
```
```bash
$ git checkout [branch-name]
```
```bash
$ git branch -d [branch-name]
```

## Synchronize changes

```bash
$ git fetch
```

### 1. Blank commits

```bash
git commit --allow empty -m 'it works!'
```

### 2. View a file of another branch
```bash
$ git show main:README.md
```

-----
`git reflog`

`git reset HEAD@{index}`

`git add . # or add individual files`

`git commit --amend --no-edit`

`git commit --amend`

`git reset HEAD~ --hard`

