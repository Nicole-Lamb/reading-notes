# Revisions and the Cloud

## Welcome to More Git FAQs! Now with Version Control. (ACP)

### Q: What is Version Control?

A: It is a snapshot of your work that can be reverted back to. It's a way to undo work or branch off and experiment when writing code or anything! You could do this to a word doc if you wanted.

    You can check your status through the terminal by following each step with `git status` to see the current state of changes or staging (added files).*

### Q: What is cloning in Git?

A: It makes a copy of a project (hence, clone) and allows you to bring it into your local (your computer) to work on it outside of GitHub.

### Q: What is the command to track and stage files?

A: `git add <fileName>` or `git add .` (which does all files within that folder - the dot stands for all).

### Q: What is the command to take a snapshot of your changed files?

A: `git commit -m` will commit your changes, meaning it sends it to GitHub as a snapshot of your changes. The -m means message so you can include why you made changes set within `"<your words here>"`

### Q: What is the command to send your changed files to Github?

A: `git push` will send your commited changes (or snapshot) to GitHub. Once this is done, your branch should be up-to-date and identical in both locations - local (your computer) as well as remote (GitHub).
