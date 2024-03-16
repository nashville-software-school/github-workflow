[Home](./README.md)

# Create a Branch

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Feature Branch

When you are ready to work on a new feature, or continue work on a feature that was started in a previous branch.

```
git switch -c feature/{feature name}
```

The `-c` creates the branch before switching to it.

## Bug Branch

When you are ready to work on a new feature, or continue work on a feature that was started in a previous branch.

```
git switch -c bigfix/{bug}
```

The `-c` creates the branch before switching to it.

### Related Guides

* [Deleting a branch](./BRANCH_DELETE.md)
* [Rebase your branch with develop](./BRANCH_UPDATE.md)
