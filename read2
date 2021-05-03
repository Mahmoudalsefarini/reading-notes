What is a branch?
 
*A branch is nothing but a pointer to the latest commit in the Git repository. So currently our master branch is a pointer to the second commit “demo.txt file is modified”.

Why are multiple branches needed?
Multiple branches are needed to support multiple parallel developments. Refer the image below to see how branches work.

Commit 1 and commit 2 were done in the master branch. After commit 2 a new Branch called as “Test” is created, and commit 3 and commit 4 are added to the test branch.

Different commit 3 and commit 4 are added to the master branch. Here we can see that after Commit 2, two parallel developments are being done in 2 separate branches.

The Test Branch and the Master Branch have diverged here and have different code — the code from Test Branch can be merged with the Master branch using git merge. This will be covered later.

Create a New Branch in Local
Create a new branch called test using the following command:

git branch test

This command creates the test branch.

We are still in the context of the master branch. In order to switch to the test branch. use the following command:

git checkout test

Now we are in the test branch.

You can list out all the branches in local using the following command:

git branch

Do Some Commits in the New Branch

Modify demo.txt by adding the following snippet:

Initial Content Adding more Content Adding some Content from test Branch

Now stage and commit using the following commands:

git add demo.txt git commit -m "Test Branch Commit"

This commit was done in the Test Branch, and now Test Branch is ahead of Master Branch by 1 commit — as the test branch also includes the 2 commits from the master branch.

You can verify the commit history in Test Branch using:

git log
