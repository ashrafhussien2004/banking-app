# Task 2

## 1. What happens when you use `git stash pop` vs `git stash apply`?
- `git stash apply`: Applies the stashed changes to your working directory **without removing** them from the stash list
- `git stash pop`: Applies the stashed changes **and removes** that stash from the list

## 2. What is the purpose of `git stash save "message"`?
- It allows you to **give a descriptive message** to your stash so you can easily identify it later in the stash list.

## 3. How can you stash changes for specific files instead of the entire working directory?
- `git stash push f1 f2`

## 4. How can you check which files were affected in a particular stash?
- `git stash show stash@{0}`
