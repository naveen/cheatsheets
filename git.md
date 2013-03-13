## git ##

undo files from an accidental 'git add .' (unstage)

	git add . # oops
	git reset HEAD filename

tig-like single-line pretty log

	git log --oneline --decorate

simple status view

	git status -sb

show last commit matching a regex ('nike')

	git show :/nike

prune branches in local when others remove remote branches

	git remote prune origin

rename a remote branch (by deleting and recreating on the remote)

	git branch -m master master-old
	git push remote :master # delete master on remote
	git push remote master-old # create master-old on remote
	git checkout -b master some-ref # create a new local master
	git push remote master # create master on remote

