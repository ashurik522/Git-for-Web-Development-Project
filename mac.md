## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an Open Source Distributed Version Control System.

2. What is the difference between Git and GitHub?
Git is the control system as opposed to GitHub which is a cloud based git hosting services used to host source code, collaborate, and interface with the version control functions of git.

3. Why do we create a branch? 
Branches make a working copy of a repo that won't change the original source code of the main/master file. 

4. What is the purpose of a Pull Request?
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git switch "andrew-shurik"

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch - downloads the commits that a remote repo has but are missing from our local repository
git merge - integrates another branch into your current working branch (merging any 2 branches)
git pull - bring a local branch up-to-date with its remote version 
Fetch ensures that you download all neccesary items needed locally without updating your current branch. Git pull will merge the remote repo with your current repo/branch and make changes to your local branch. 

7. What is a merge conflict?
Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

8. How do you resolve a merge conflict?
Merge conflicts are resolved by selecting which changes of a commit to keep. This can be done by pulling up the status and identifying the conflicts. Then those commits need to be evaluated side by side to create a new commit with the correct changes. 
