# TASK:1


**Qs.1 What do you mean by git and GitHub?**
Ans. Git is a software that runs on your computer and manages your files.Git is a free and open source distributed version to handle everything from small to very large projects.
GitHub is an online platform that allow you to synchronise your local reporitory onto the web.you can also use github to browse other people's repositories and download code or document without using git.

**Qs.2 Why Git Hub is so popular and used in most of projects.**
Ans. GitHub is a Git repository hosting service,which provide a web based graphical interface. Github is one place where project managers and developers coordinate, track and update their work ,so that project stay transparent and on schedule.
Allows us to create and manage versions, so that if the latest version fails, we can always go back to older version(s).
Two or more developers may add code to the same file and a centralized SCM enables us to combine these lesser conflicts.

**Qs.3 What is version control system.How Git is a VCN?**
Ans. VCN is a Type of System that allow you to keep track of changes made to your code over time,so that you can recall specific version later.
Git is a distributed version control system for tracking changes to source code during software development.
..In centralized version control, each user gets his or her own working copy, but there is just one central repository. As soon as you commit, it is possible for your co-workers to update and to see your changes. For others to see your changes, 2 things must happen:
You commit
They update.

**Os.4 What are the other platform similar to GetHub?**
Ans.Gitlab
Bitbucket
Launchpad
Sourceforge

**Qs.5 Why are you interested in learning of Git and Github?**
Ans.Git simplifies the process of working with other people and makes it easy to collaborate on projects. Team members can work on files and easily merge their changes in projects.


# TASK:2

**Qs.1 How git work flow work?**
Ans.A Git Workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. Git workflows encourage users to leverage Git effectively and consistently. Git offers a lot of flexibility in how users manage changes.

**Qs.2 What are the different stages of a git project as commit ,add?**
Ans.The 3 stages are.
Modified:
a repository is basically a kind of a directory that contains all the files related to your code. So, in the repository we can write code, and maintain it. Once, the code is written, anyone willing to make some modification can make those changes in their own remote repository.
Staged:
we can make changes to the project without hampering the original version, but how do we apply those changes to our remote repository? So, we use the commands in the Git command line � git add. So, this command tracks the new changes and pushes it to the staging area. So, staging area is place prior to the actual implementation of changes, i.e. this area contains all the added files that contain new code.
Commit:
This is the final stage, as this stage finally applies the new changes to the remote repository. Looking at the previous analogy, this is your �Go' position. So, a commit is a set of new files that are being added to a project as part of the modification. Each commit represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code.

**Qs.3 Is it possible to do a git comit before git add.if you have made any changes.**
Ans.yes we can perform git commit comand before git add by using git commit-a command .
No i don't made any changes.

**Qs.4 Why is git diff used?**
Ans.Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them. It is not necessary that these inputs are files only

**Qs.5 Can we leave the commit message as blank.**
Ans.Git generally requires a non-empty message because providing a meaningful commit message is part of good development practice and good repository stewardship.
But we can leave the commit message blank.


# Task:3

**Qs.1 What is meant by the term fork and clone?**
Ans. A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

Cloning a repository means that you're downloading a copy of the source code from source control. To use the iOS SDK you have to download the code from GitHub (ie- clone the iOS SDK repository).


**Qs.2 What is branches in github?**
Ans.A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. ... One word: the master branch is deployable.Use a branch to isolate development work without affecting other branches in the repository. 

**Qs.3 What is PR?**
Ans.Pull requests are a feature specific to GitHub. They provide a simple, web-based way to submit your work (often called �patches�) to a project. It's called a pull request because you're asking the project to pull changes from your fork.

**Qs.4 Can we delete the master branch .if not,why?**
Ans.Yes,we can delete the master branch.
you need to change your GitHub repo default branch. You need to go to the GitHub page for your forked repository, and click on the �Settings
 button.

Click on the "Branches" tab on the left hand side. There's a �Default branch� dropdown list near the top of the screen.

From there, select placeholder (where placeholder is the dummy name for your new default branch).

Confirm that you want to change your default branch.
Now you can do (from the command line):
git push origin :master


**Qs.5 How can we delete a Branch?**
Ans.Delete a branch with git branch -d <branch> . The -d option will delete the branch only if it has already been pushed and merged with the remote branch. Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet.


https://github.com/codewayy/github_series-2/pull/5
