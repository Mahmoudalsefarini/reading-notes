# What is a branch?
 

 ![](https://blog.udemy.com/wp-content/uploads/2015/08/image086.png)

*A branch is nothing but a pointer to the latest commit in the Git repository. So currently our master branch is a pointer to the second commit “demo.txt file is modified”.

Why are multiple branches needed?

Multiple branches are needed to support multiple parallel developments. Refer the image below to see how branches work.

Commit 1 and commit 2 were done in the master branch.

 After commit 2 a new Branch called as “Test” is created, and commit 3 and commit 4 are added to the test branch.

Different commit 3 and commit 4 are added to the master branch. Here we can see that after Commit 2, two parallel developments are being done in 2 separate branches.

The Test Branch and the Master Branch have diverged here and have different code — the code from Test Branch can be merged with the Master branch using git merge.

Create a New Branch in Local


## Rebasing

![](https://blog.udemy.com/wp-content/uploads/2015/08/image046.png)

A popular alternative to merging is rebasing.

The Basics

Rebasing starts with the common ancestor of two branches: the one you’re on and the one you’re rebasing onto. Then, the diffs resulting from each commit of your current branch are saved to temporary files, and the current branch gets reset to the same commit as that of the branch you are rebasing onto. Last but not least, all changes get applied to the branch you are rebasing onto.

This process essentially rewrites a project’s history by replaying all changes committed on one branch to another one, leading to cleaner application of commits on a remote branch and a linear history.