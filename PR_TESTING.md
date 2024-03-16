[Home](./README.md)

# Testing a Teammate's Pull Request

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

Do not begin reviewing a teammate's Pull Request until is has a complete description of the changes and steps to test.

## Testing the feature or bug

```bash
# Make sure you have no changes to be committed
# Add and commit changes if there are any
git status

# Get all of the latest branchs from Github
git fetch origin

# Switch to your teammate's branch
git switch {branch name}
```

Then follow the steps provided by your teammate in the PR description.

## Review and feedback

Whether you discover any issues during testing, or not, you **must** review your teammate's code and provide feedback.

Watch the [How to Review a Pull Request in GitHub the RIGHT Way](https://www.youtube.com/watch?v=lSnbOtw4izI) video for a guide on how to review code as a professional.

### Related Guides

* [Creating a Pull Request](./PR_CREATE.md)
* [Merging a Pull Request](./PR_MERGE.md)
* [Rebasing your branch with develop](./PR_UPDATE.md)