# Summary of Commands

- `git init` - This is where the magic starts. Creates a new, empty repository on your computer.
- `git status` - What's going on in git's head? It's the "what am I looking at" of a git repository.
- `git add` - Adds a file's changes to the staging area. Lets you pick and choose what changes you want to record.
- `git restore` - When you've been editing a file, but want to roll back before committing
- `git commit` - Records your edits for the record books in a commit. Works a lot like a checkpoint as you're working through a tough level.
- `git log` - Take a trip down memory lane, see the commit history
- `git remote` - Ready to start pushing code around, so you can "git" it from somewhere else later? This will link things up.
- `git push` - Beam me up scotty! Sends all your committed changes to the remote repository you setup with git remote. Sends things from your computer to the interet. This command is what we use to push to a remote repository in git speak.
- `git reset` - Throw out commits that you don't want to push anymore.
- `git fetch` - Make the minion check the mail for you. See if there's been anything new up on the remote.
- `git pull` - Incoming transmission... Retrieves the latest changes from the remote repository and merges them into your copy.
- `git clone` - Make your own copy of a repository so that you can work on it. Automatically sets the `origin` remote for you.

## All this git speak... How do I keep track of it?

- `git help glossary` is your friend. It will pull up a document that has all the funny terms defined.
- `git help <command>` will help you keep track of the specifics involved in each command.

## Navigating the history

- `git checkout` - This is your time machine. Lets you reverse the clock and go back in time. Can also be used if git restore is not available.
- `git diff` - Compare your files between to points in time.

## Make working on stuff easier

- `git stash` - Started working on something, but not ready to commit? Need to move to a different point in time? Stash gives you a nice place to store your work-in-progress.
- `git tag` - Want to mark a specific point in time so you can come back to it, here's git's sticky note label for your history.
- `git branch` - Ever want to work on something without messing up your hard work, git branch is your friend.
- `git merge` - Incorporate work from one branch into another. What you hope to eventually do with most branches you make.
- `git rebase` - Put your commits on the wrong branch? move them with rebase. There's a bit more to this one though, it's quite powerful.
- `git reflog` - When you deleted something you wish you didn't (like a branch)!
- `git revert` - Broke something in a commit that you pushed? Undo it!
- `git blame` - Figure out who last modified something - This will be more interesting when you're not the only person making commits.
- `git bisect` - Track down a hard-to-find bug. Makes things much easier to track down what specifically broke something.