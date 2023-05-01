# 23-01-05-git

- 'git init': initialize git repository (repo)
	- do not nest git repos
- 'git status': tell you things about what's going on in git
- 'git add': add a file to the staging area
- 'git commit': commit changes from staging area to git repo
- 'git commit -m "message": add msg as you commit
- 'git log': show reverse order of all commits
	- 'git log --oneline'
	- 'git log --oneline --all'
- 'git diff': diff all modified files in repo
	- 'git diff filename': diff a specified file
	- 'git diff --staged': diff staged area, after add
	- 'git diff HASH/HEAD'
- 'HEAD': tell you where you are now (at most recent commit)
- 'git checkout <HASH>: move HEAD to hash
	- will be in a HEAD detached state
	- git switch -
	- git switch Master

