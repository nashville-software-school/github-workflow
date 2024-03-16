[Home](./README.md)

# Creating Pull Request

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Push your branch

```bash
# Make sure you have no changes to be committed
# Add and commit changes if there are any
git status

# Push branch to Github
git push origin {branch name}
```

## Create Pull Request

1. Go to the **Pull Requests** tab on the Github repository.
2. Create a new one.
3. Make sure that `develop` is chosen as the **base** branch.
4. Make sure that your branch is chosen as the **compare** branch.
5. Follow the guidance in the [Writing A Great Pull Request Description](https://www.pullrequest.com/blog/writing-a-great-pull-request-description/) article to make a high value pull request for your teammates to test your code.
6. Broadcast to your teammates that there is a new Pull Requests to review.

Wait to be alerted that one, or more, teammates have reviewed your code and then follow the process to [merge your changes](./PR_MERGE.md).

### Related Guides

* [Updating a Pull Request](./PR_UPDATE.md)
* [Merging a Pull Request](./PR_MERGE.md)
* [Rebase your branch with develop](./BRANCH_UPDATE.md)
