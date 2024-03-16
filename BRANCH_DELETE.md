[Home](./README.md)

# Delete a Branch

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Delete Local Branch

```bash
git branch -d {branch name}
```

## Delete a Remote Branch

Note the colon `:` below in the command. That must be there.

```bash
git push origin :{branch name}
```

### Related Guides

* [Create a branch](./BRANCH_CREATE.md)
* [Rebase your branch with develop](./BRANCH_UPDATE.md)
