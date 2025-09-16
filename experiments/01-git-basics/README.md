# Experiment 01: Git Basics

## Objective
Learn fundamental Git operations and version control concepts essential for DevOps practices.

## Prerequisites
- Git installed on your system
- Basic command line knowledge
- GitHub account (for remote operations)

## Learning Outcomes
After completing this experiment, you will be able to:
- Initialize a Git repository
- Stage and commit changes
- Work with branches
- Collaborate using remote repositories
- Resolve merge conflicts

## Experiment Steps

### Part 1: Repository Setup
1. Create a new directory for this experiment
2. Initialize a Git repository
3. Configure user name and email
4. Create an initial commit

### Part 2: Basic Operations
1. Create and modify files
2. Use `git add` and `git commit`
3. View commit history with `git log`
4. Check repository status

### Part 3: Branching
1. Create a new branch
2. Switch between branches
3. Merge branches
4. Delete branches

### Part 4: Remote Operations
1. Add a remote repository
2. Push changes to remote
3. Pull changes from remote
4. Clone a repository

### Part 5: Collaboration
1. Fork a repository
2. Create a pull request
3. Review and merge changes
4. Handle merge conflicts

## Commands Reference

```bash
# Repository setup
git init
git config user.name "Your Name"
git config user.email "your.email@example.com"

# Basic operations
git add <file>
git commit -m "commit message"
git status
git log

# Branching
git branch <branch-name>
git checkout <branch-name>
git merge <branch-name>
git branch -d <branch-name>

# Remote operations
git remote add origin <repository-url>
git push -u origin main
git pull origin main
git clone <repository-url>
```

## Expected Results
Document your observations and results:

1. What happens when you commit without staging?
2. How does Git track file changes?
3. What's the difference between `git fetch` and `git pull`?
4. How do you resolve a merge conflict?

## Troubleshooting

### Common Issues
- **Authentication errors**: Check your GitHub credentials
- **Merge conflicts**: Use `git status` to identify conflicted files
- **Detached HEAD**: Create a new branch from the current state

### Useful Commands
```bash
git reset --hard HEAD~1  # Undo last commit
git stash                # Temporarily save changes
git stash pop            # Restore stashed changes
```

## Further Reading
- [Pro Git Book](https://git-scm.com/book)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

## Submission
Create a `results.md` file documenting:
- Commands you executed
- Challenges you faced
- Solutions you found
- Key learnings from this experiment