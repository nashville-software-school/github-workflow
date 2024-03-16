[Home](./README.md)

# Updating Your Branch After PR is Merged

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

When a teammate's code has been merged into the `develop` branch on Github, at your earliest possible convenience, you should rebase your current work on the latest code in `develop`.

```bash
# Checkout the develop branch
git checkout develop

# Pull the latest changes from the remote repository
git pull

# Checkout your feature branch
git switch {your branch name}

# Rebase your branch with the latest develop branch
git rebase develop
```

### Related Guides

* [Fixing Merge Conflicts](./MERGE_CONFLICTS.md)
* [Creating a feature branch](./BRANCH_CREATE.md)