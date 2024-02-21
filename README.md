# repo11

git status

git diff -see different

git add . -add to saving progress ,file 變綠色

git commit -m - save on computer

git push origin main - publish on github

git log - record

git pull origin main - get resources from git

<<<<<<< HEAD
git pull --rebase origin master

git push --force

Create new branch
git checkout -b Branch_Name -create branch

git branch - check branch

git checkout Branch_Name -move to specify branch

git branch -d name -delete branch

Modify (add/commit)

git push --set-upstream origin Branch_Name

To push your changes from your personal branch to the GitHub organization's repository, you can follow these steps:

1. Add the organization's repository as a remote:
   ```
   git remote add organization <organization_repository_url>
   ```
2. Verify that the remote has been added successfully:
   ```
   git remote -v
   ```
   You should see both your personal remote (usually named "origin") and the organization's remote (named "organization" in this example).
3. Push your branch to the organization's repository:
   ```
   git push organization <your_branch_name>
   ```
   Replace `<your_branch_name>` with the name of your personal branch.
4. Enter your GitHub credentials (username and password) if prompted.
5. After pushing, your changes should be available in the organization's repository under your branch.
   Note: Make sure you have the necessary permissions to push to the organization's repository. If you don't have write access, you may need to create a pull request instead and wait for it to be merged by someone with the appropriate permissions.
