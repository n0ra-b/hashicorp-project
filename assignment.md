## Understand git commands: push, fetch, and pull
Use `git push`, `git fetch`, and `get pull` to manage code between your local repository and a remote repository.

### Git push
Use `git push` to send changes from your local branch to a remote repository. If the remote branch has new changes that you haven't downloaded locally then the push will fail. To avoid this, synchronize your local branch with the remote repository using `git pull` or `git fetch` followed by `get merge`.

### Git fetch
Use `git fetch` to download changes from a remote repository into your tracking branch without merging them in your local branch. This gives you a chance to review the changes before merging them. To merge these changes into your local branch, use `git merge`.

### Git pull
`git pull` combines `git fetch` and `git merge` into a single command by downloading changes from a remote repository and merging them into your local branch. 

By understanding the differences between `git push`, `git pull`, and `git fetch`, you can effectively manage code collaboration between local and remote repositories.
