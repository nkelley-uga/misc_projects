# Git and GitHub Tutorial

---

![alt text](https://imgs.xkcd.com/comics/git.png)

---

# Workflow Quick-Reference

The essential chunk of code - use this and you're 99% there.

```
git pull
<add code, etc.>
git add <filename> (use * to add all files)
git commit -m '<message here>'
git pull (avoid tangled commits)
git push
```

---
---

# 1) Setup

These steps are only required once.

1. [Go to GitHub](https://github.com/) and create an account with a valid email address.
2. [Download the proper version of git for your OS.](https://git-scm.com/)
3. Open up your terminal, check for git:
    * ```$ git --version```
4. Check your configurations:
    * ```$ git config --list```
5. If you don't see your name and email:
    * ```$git config --global user.name "<your name on GitHub>"```
    * ```$git config --global user.email "<your email on GitHub>"```
    
---
    
# 2) Cloning
    
These steps are required every time you need to work with a new repository.
    
**Clone vs Fork:** Making a **clone** gives you a private copy of a repo; only you will see any changes made, so this will mainly be used for testing. A **fork** creates a local repo in your GitHub account; you can request to merge any changes with the master repo.
    

    
---
    
# Some Useful Links
    
* [GitHub Desktop](https://desktop.github.com/)
* [GitHub Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code)
* [Markdown Math Reference](https://www.calvin.edu/~rpruim/courses/s341/S17/from-class/MathinRmd.html)
* [Simple Git Guide](http://rogerdudler.github.io/git-guide/)
* [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials)