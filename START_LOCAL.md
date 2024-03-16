[Home](./README.md)

# Begin a Project Without Starter Code

This guide is for when your team is not given an existing Github repository at the beginning of the project.

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Initializing the Repository

The following steps must be done by one, and only one, teammate. Everyone else wait until these steps are completed.

1. Change to the workspace directory in your terminal with.
    ```sh
    cd ~/workspace
    ```
2. Create a directory for your project, and navigate to that directory.
    ```sh
    mkdir {project name}
    cd {project name}
    ```
3. Create a default documentation file for the project.
    ```sh
    touch README.md
    ```
4. Run the `git init` command.
5. Run `git add README.md`.
6. Run `git commit -m "Initial commit"`
7. Go to your cohort's Github organization.
8. Create a new repository by clicking the **New** button.
    * Provide a brief, but accurate name for it.
    * Do not check the _Create a README file_ checkbox.
    * Click the button at the bottom to create the repository
9. Click the **Code** button.
10. Ensure that **SSH** option is chosen, and not **HTTPS**.
11. Copy the connection string provided.
12. Back in your terminal run the following command.
    ```sh
    git remote add origin {connection string}
    ```
13. Run `git push -u origin main` to push your first commit to Github.
14. Run `git switch -c develop` to create the active development branch.
15. Run `git push -u origin develop` to create the branch on Github.
16. Share the public URL to the repository with your team.

## Cloning the Repository

Everyone else on the team should follow these steps now.

1. Visit the URL your teammate shared.
2. Click the **Code** button.
3. Ensure that **SSH** option is chosen, and not **HTTPS**.
4. Copy the connection string provided.
5. Back in your terminal run the following commands.
    ```sh
    cd ~/workspace
    git clone {connection string}
    ```


### Related Guides

* [Begin a Project With Starter Code](./START_REMOTE.md)
* [Creating a feature branch](./BRANCH_CREATE.md)
