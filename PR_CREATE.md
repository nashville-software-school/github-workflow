[Home](./README.md)

# Creating Pull Request

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Ensure you have the latest

Before you create a pull request, you need to make sure you have the latest version of `develop` merged into your branch, or the code could be out of date - and you don't want that.  Follow the "[Rebase your branch with develop](./BRANCH_UPDATE.md)" guide to make sure that the code on your branch is the freshest.

If there are any merge conflicts, watch the [EXTREMELY helpful guide to merge conflicts](https://youtu.be/HosPml1qkrg?t=140) video to fix the conflict in Visual Studio Code.

## Push your branch

Time to push your code to Github and create a pull request. Pull requests are attached to branches, not commits, so you can do this step as many times as you need.

```bash
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
