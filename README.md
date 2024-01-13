# Assignment on Git and Version Control

## Explain Version Control

Version Control is the process of tracking or recording and managing changes that have been made on a file over a period of time so as to be able to recall or revisit specific versions of the file later for better understanding of the lifecycle and for file integrity.

## Explain the difference between git and github

Git is a version control system that allows the user to record and manage changes to their code while GitHub is a web-based service that allows you to store and access your git repositories on the cloud.

## List 3 other GitHub alternatives

- Apache Subversion
- Bitbucket
- AWS CodeCommit

## Explain the Difference between git fetch and git pull  

Git fetch command allows you to download changes from the remote repository into your local repository without making any changes to your working directory. With git fetch,it allows you to review the changes to ensure that there are no conflicts before merging with your working directory.

On the other hand, git pull command downloads the latest changes from the remote repository into the local repository and automatically merges the changes with your working directory.

## Explain in simple terms git rebase and the command for it

Git Rebase is a command that integrates changes from one branch by transplanting that branch onto the tip of another branch. By doing this, you achieve a cleaner and more linear commit history.

The command for git rebase is [code] `git rebase <dest branch>` where dest branch represents the branch that your current branch commits will be transplanted to.

## Explain in simple terms git cherry-pick and the command for it

Git cherry-pick allows you to pick a specific commit/commits from one branch and apply it to another branch without applying all the commits from that branch.

The command syntax is `git cherry-pick <commit-hash>` where commit-hash is the identifier of the commit that you want to cherry-pick.

To cherry-pick multiple commits, the syntax is `git cherry-pick  <start commit-hash>^..<end commit-hash>`
