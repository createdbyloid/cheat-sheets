## How to Reset a Local Branch to Remote Tracking Branch

1. Save the current state of your local branch (optional).
```bash
git commit -a -m "I am saving my work"
git branch backup_work
```

2. Fetch the latest version of the code from the remote.
```bash
git checkout main
git fetch origin
```

3. Reset the local branch.
```bash
git reset --hard origin/main
```

4. Clean up files (optional).
	The `-x` flag removes ignored files.
	The `-d` flag removes untracked folders.
	The `-f` flag removes untracked files.
```bash
git clean -xdf
```

