[Home](./README.md)

# Production Ready Merge to Main

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Definition of Done

When a feature or bug ticket that your team is working on for the sprint reaches the Definition of Done _(refer to the Rules of Engagement on the Learning Platform)_, then you can do a production release.

## Create a tag for a release

One teammate must complete these steps. If this is your first tag and release, your version number will be **1.0.0**. Read the [semantic versioning](https://semver.org/) guide for how to increment the major, minor, and patch numbers.

```bash
# Switch to develop branch
git switch develop

# Make sure you have the latest
git pull

# Create a release tag
git tag {version number}

# Push tag to Github
git push origin {version number}
```

## Create release pull request

1. Create a new pull request.
2. Choose `main` as the **base** branch.
3. Choose `develop` as the **compare** branch.
4. Record what is in this release. See template below.
5. Have a teammate review it for completeness.
6. Merge it to `main`.
7. Broadcast to your team that there is a new production release and that `main` should be pulled at their earliest convenience.


### Release pull request template

```txt
## Release Notes for [VERSION_NUMBER]

### Added
- [List of new features or improvements added]

### Changed
- [List of changes made to existing functionality]

### Fixed
- [List of bug fixes or resolved issues]

### Other Notes
- [Any additional information, breaking changes, or caveats that users should be aware of]

[OPTIONAL] Closes #[ISSUE_NUMBER1], #[ISSUE_NUMBER2], ...
```


### Related Guides

* [Creating a Pull Request](./PR_CREATE.md)
* [Rebasing your branch with develop](./PR_UPDATE.md)