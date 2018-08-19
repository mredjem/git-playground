# git-playground

Playground to test git commands

## Getting started

**Clone**

```bash
git clone https://github.com/mredjem/git-playground.git
```

## Making commits

**Stage changes**

```batch
git add .
```

**Commit**

```bash
git commit -m ":tada: New commit!"
```

**Amend**

```bash
git --amend -m "Override previous commit message"
```

## Branching

**New branch**

```bash
git branch new-branch
```

**New branch with checkout**

```bash
git checkout -b new-branch
```

**New branch from commit**

```bash
git checkout -b new-branch <commit_id>
```

**Switch branch**

```bash
git checkout master
```

## Tracking

**Push branch to origin**

```bash
git push -u origin new-branch
```
