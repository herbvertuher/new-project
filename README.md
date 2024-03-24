
# 1. Task description:
Jira Ticket:

Task Title: Set up new Git repository and create development branch for 'new-project'

Task Description:

As a developer, I need a new GitHub repository for 'new-project' and i need a development branch so that I can work on new features without affecting the main branch.
Readme file should contain step-by-step instructions on how we can do it ourselves.

Expected Results:

A new branch called "development" is created and the user is able to switch to it successfully.
A new file called "README.md" is created and step-by-step instructions is added to it successfully.
The changes to the "development" branch are committed with a commit message successfully.
The changes from the "development" branch are merged into the "main" branch successfully.

Definition of Done (DoD):

Link to new-project Readme file

# 2. Step-by-step instruction:

1. Create new branch `development`:
```shell
git branch development
```
2. Switch to `development` branch:
```shell
git checkout development
```
3. Add `README.md` to the index:
```shell
git add README.md
```
4. Create a commit in the `development` branch:
```shell
git commit -m "update instruction"
```
5. Switch to `main` branch:
```shell
git checkout main
```
6. Merge `development` to `main`:
```shell
git merge development
```
7. Check status:
```shell
git status
```
8. Push changes to GitHub:
```shell
git push --all origin
```
