SecretStore is a secret manager that uses public/private keys to encrypt secrets so that they can be easily shared between team members

How it works:
1. ss add {dir}
	This will start tracking the {dir} directory.

2. ss commit
	Similar to `git commit`, this will commit changes to the tracked files/directories

3. ss push
	Similar to `git push`, this will push the committed changes to remote repo

4. ss update
	This will pull and apply new commits from remote repo.

## Aspirational features
5. ss publish
	This will publish changes in the remote repo to all the local repos. This can be executed after each update to remote repo so that all team members will get the latest secrets without pulling
