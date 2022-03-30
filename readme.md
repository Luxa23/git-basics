# Git Cheatsheet

## git repository

- `git init` - erstellt neues leeres repository lokal 
- `git status` - zeigt branch, commits, untracked files

## commit

- `git add` - bringt alle Änderungen auf stage, die committed werden sollen
- `git commit -m <commit message>` - committed changes, die auf stage sind inkl. Notiz zu Änderungen
- `git log` - log der letzten commits inkl. message

## how to return to save points

- `git restore <file name>` - stellt eine frühere Version wieder her
- `git restore --staged <file name>` - stellt eine frühere Version inkl. Content wieder her

## remote repository

- `git remote add origin <ssh link>` - verknüpft lokales und online repository (online repository muss vorher in git angelegt werden)
- `git remote -v` - prüft neu verknüpfte repositories 
- `git push -u origin <branch name>` - bringt lokale Änderungen eines bestimmten branches auf ein remote repository 
- `git push` - 
- `git pull -u origin <branch name>` - bringt remote Änderungen eines bestimmten branches im repository ins lokale repository
- `git pull`

## branching

- `git branch` - List, create, or delete branches.
- `git branch <branch name>` - ruft genannten branch auf
- `git switch` - wechselt zwischen zwei Branches
