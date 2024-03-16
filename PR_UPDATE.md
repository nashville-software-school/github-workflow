[Home](./README.md)

# Updating Pull Request

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

There are times when a teammate requests changes on your PR. There may be bugs, or your code may need to be improved for readability or efficiency.

## Switching to branch

If you are currently working on another ticket, switch back to PR branch.

```bash
# Make sure you have no changes to be committed
# Add and commit changes if there are any
git status

# Switch to branch attached to PR
git switch {branch name}
```

Make any changes, or fixes, that were requested by your teammate(s). Make sure you thoroughly test it.

```bash
git push origin {branch name}
```

Then broadcast to your teammates that the PR has been updated and ready to be tested again.

### Related Guides

* [Merging a Pull Request](./PR_MERGE.md)
* [Rebase your branch with develop](./BRANCH_UPDATE.md)
