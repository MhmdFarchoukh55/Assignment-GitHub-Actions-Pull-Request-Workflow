## Process

1- Switched to a new branch:
   `git switch -c feature/add-workflows`

2- Created the GitHub Actions directory:
   - `.github/`
   - `.github/workflows/`

3- Navigated to the workflows folder:
   `cd .github/workflows`

4- Created the first workflow file:
   `manual-trigger.yml`

5- Opened the file and added a manual trigger workflow using `workflow_dispatch`.

6- Committed and pushed the changes to the branch:
   `feature/add-workflows`

7- Created a second workflow file:
   `merge-to-main.yml`

8- Added a workflow that runs on push to the `main` branch and logs a message.

9- Opened a Pull Request from:
   `feature/add-workflows → main`

10- Merged the branch into the `main` branch.