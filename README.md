# Git Workshop

This workshop is about learning how to use Git. In THIS repository, go crazy and make all the crazy commits you want. Here we will experience the reason Git Flow is so necessary.

> WINDOWS USERS: [Download GitBash](https://gitforwindows.org)

## 1. Clone
Cloning a repository means grabbing the whole remote repisitory and downloading it to your computer.

Open your terminal, navigate to your ~favorite~ directory, and run:
```
git clone https://github.com/dali-lab/Git-Workshop.git
```

## 2. Start commiting
To make a file's changes ready for commit (stage the changes), run:
```
git add [fileName]
```

To commit all of the staged changes:
```
git commit -m "Youre message here"
```

To create a new branch:
```
git branch [branchName]
```

To switch to a branch:
```
git checkout [branchName]
```

To push commits from the current branch to a remote branch:
```
git push origin [branchName]
```
