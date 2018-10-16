[![CircleCI](https://circleci.com/gh/beardofedu/wtd-things.svg?style=svg)](https://circleci.com/gh/beardofedu/wtd-things)

# How to Git - Things to do in Portland
Welcome to one of the repositories we will be using in today's workshop. 
Our GitBook available as a PDF here: https://www.gitbook.com/book/beardofedu/wtd-things/details

## Resources

- [GitHub for Developers Manual](https://github.github.io/training-manual/)
- [Git Cheat Sheets](https://services.github.com/resources/)
- [Introduction to GitHub Flow](https://guides.github.com/introduction/flow/)
- [Authentication Troubleshooting Guide](https://help.github.com/categories/authenticating-to-github/)
- [git-scm](https://git-scm.com)
- [GitSchool - Visualizing Git](http://git-school.github.io/visualizing-git/)
- [LearnGitBranching](http://learngitbranching.js.org/?NODEMO)

### Class Images
- [Git Configuration Levels](https://services.github.com/on-demand/images/config-levels.jpg)
- [The Two Stage Commit](https://services.github.com/on-demand/images/two-stage-commit-a.jpg)
- [Reset Modes](https://services.github.com/on-demand/images/reset-modes.jpg)

## Scripts for Adding Files

- **Bash:** `for d in {1..6}; do touch file$d.md; git add file$d.md; git commit -m "adding file $d"; done`
- **PowerShell:** `for ($d=1; $d -le 6;$d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md";}`

@beardofedu!
