[Home](./README.md)

# Begin a Project With Starter Code

This guide is for when your team is provided with a Github repository with existing code in it. You should not use this guide if you have not been provided with a existing repository.

> **Tip:** Remember that curly braces in commands below should not be typed by you. They indicate that you should place your own value there without curly braces.

## Before cloning

One teammate must complete these steps before anything else happens.

1. Change to the workspace directory in your terminal with.
    ```sh
    cd ~/workspace
    ```
2. Clone the repository.
    ```sh
    git clone {ssh connection string}
    ```
3. Run the `ls` command to view the new directory that was created.
4. Use the `cd {directory name}` command to navigate into that directory.
5.  Run `git switch -c develop` to create the active development branch.
6.  Run `git push -u origin develop` to create the branch on Github.

## After develop exists

Once the develop branch exists, all other teammate follow these steps.

1. Change to the workspace directory in your terminal with.
    ```bash
    cd ~/workspace
    ```
2. Clone the repository.
    ```bash
    git clone {ssh connection string}
    ```
3. Run the `ls` command to view the new directory that was created.
4. Use the `cd {directory name}` command to navigate into that directory.
5. Switch to the **develop** branch.
    ```bash
    git switch develop
    ```


After the team reviews the project requirements and you are ready to start working on the feature assigned to you, [create a branch](./NEW_BRANCH.md) for the work.

### Related Guides

* [Begin a Project Without Starter Code](./START_LOCAL.md)