# Git Notes

## Common Commands

```bash
git add <file>									# Add single file to stage
git add -A										# adds all files not ignored to stage
git commit -m '<msg>'							# commits what has been staged
git status										# Where you are (branch) what has been added or removed or needs add/removed

git branch										# list of branches
git branch -D <branchName>						# Del local branch
git checkout -b <branchName>					# makes new branch
git checkout <branchName>						# switch context to target branch
git merge <branch>								# brings the commit histroy from target branch to current branch

git pull origin <branchName>					# get remote branch info and merge
git fetch origin								# get remote branch info
git push origin <branchName>					# push specified local branch to remote

git log											# list of commit info 'q' to quit
git tag -a '<v1.0.0>' -m '<release msg>'		# tag the current branches most recent commit (HEAD)

git reset --hard <id or tag or HEAD>			# revert back to target and check it out					

```