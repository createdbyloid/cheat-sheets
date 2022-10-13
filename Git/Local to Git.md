## Create a new repository on the command line
1. Create a new repository in git
	* For example "git@github.com:createdbyloid/resume.git"
2. go to local folder then run
	* Replace {git repository} to new repository
``` bash
echo "# resume" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin {git repository} 
git push -u origin main
```
