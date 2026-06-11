# stash-rebase
Why Git Stash is Useful

Git Stash is useful because it allows developers to temporarily save uncommitted changes without creating a commit. This helps keep the working directory clean while preserving ongoing work.

Benefits of Git Stash:

Allows switching between branches without losing current changes.
Helps handle urgent tasks while unfinished work is safely stored.
Prevents unnecessary or incomplete commits.
Makes it easy to pause and resume work later.
Keeps the repository history clean by avoiding temporary commits.

Example: If a developer is working on a feature and suddenly needs to fix a production issue, they can use git stash to save their current work, switch branches, fix the issue, and later restore their work using git stash pop.

Why Git Rebase Keeps History Clean

Git Rebase keeps commit history clean by moving feature branch commits on top of the latest commits from another branch instead of creating a merge commit.

Benefits of Git Rebase:

Maintains a linear and easy-to-read commit history.
Avoids unnecessary merge commits.
Makes project history easier to understand and review.
Helps teams track changes more efficiently.
Creates a cleaner repository structure in collaborative projects.

Example: If the main branch receives new commits while a developer is working on a feature branch, git rebase main places the feature branch commits on top of the latest main branch commits, making it appear as if the work was built on the most recent version of the project from the beginning.

Summary
Git Stash helps manage unfinished work by temporarily saving changes without committing them.
Git Rebase helps maintain a clean and linear commit history by replaying commits on top of the latest branch changes.

These two Git features are commonly used in professional DevOps and software development workflows to improve productivity and maintain an organized repository history.
