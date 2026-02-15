# Git Version Control Quick Reference

## Basic Setup

- **Configure user:**
	```sh
	git config --global user.name "Your Name"
	git config --global user.email "you@example.com"
	```
- **Initialize repository:**
	```sh
	git init
	```
- **Clone repository:**
	```sh
	git clone <repo_url>
	```

## Working with Changes

- **Check status:**
	```sh
	git status
	```
- **Add files:**
	```sh
	git add <file>
	git add .
	```
- **Commit changes:**
	```sh
	git commit -m "Commit message"
	```
- **View commit log:**
	```sh
	git log
	```

## Branching & Merging

- **List branches:**
	```sh
	git branch
	```
- **Create branch:**
	```sh
	git branch <branch_name>
	```
- **Switch branch:**
	```sh
	git checkout <branch_name>
	# or
	git switch <branch_name>
	```
- **Create & switch branch:**
	```sh
	git checkout -b <branch_name>
	# or
	git switch -c <branch_name>
	```
- **Merge branch:**
	```sh
	git merge <branch_name>
	```

## Remote Repositories

- **Add remote:**
	```sh
	git remote add origin <url>
	```
- **View remotes:**
	```sh
	git remote -v
	```
- **Push changes:**
	```sh
	git push origin <branch>
	```
- **Pull changes:**
	```sh
	git pull
	```

## Undoing Changes

- **Unstage file:**
	```sh
	git restore --staged <file>
	```
- **Discard changes:**
	```sh
	git restore <file>
	```
- **Amend last commit:**
	```sh
	git commit --amend
	```
- **Revert commit:**
	```sh
	git revert <commit>
	```

## Useful Tips

- **Show differences:**
	```sh
	git diff
	```
- **Stash changes:**
	```sh
	git stash
	git stash pop
	```
- **Delete branch:**
	```sh
	git branch -d <branch_name>
	```

For more, see the [Git documentation](https://git-scm.com/doc).
