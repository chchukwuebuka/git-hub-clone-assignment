# git-hub-clone-assignment

---

## Version Control

Version control in software engineering is a vital component of product development. It’s a best practice that significantly enhances efficiency, fostering faster team growth in the process. Version control is also known as versioning or source control, is the practice of tracking and managing changes to software code.

    Three key reasons why version control is important to both software developers and product/project managers:

1. Streamlined release management
It helps in maintaining different versions of software releases. These releases encapsulate various enhancements and features developed for different customers, aligning with the release roadmap.

2. Conflict prevention
Version control helps avoid code conflicts within the source code base. By maintaining separate branches for different releases, it minimizes the chance of changes overlapping and causing conflicts.

3. Tracking changes to digital artifacts
In addition to source code, version control helps track changes to other digital artifacts involved in software development. This could include technical design specifications, requirement documents, or any other deliverables that.

**Types of version control**:

1. Local version control changes are stored locally in the files as a hotfix or patch before being pushed to a single version of code in a database.
2. Central version control hosts different versions of the code in a centralized repository. Users can access these versions, and push or pull changes as needed.
3. Distributed version control is the most sophisticated of the three. Here, each local repository fully mirrors the central repository, including its history.

**Benefits of version control systems**:

Using version control software is a best practice for high performing software and DevOps teams.
Version control also helps developers move faster and allows software teams to preserve efficiency and agility as the team scales to include more developers.

1. Maintaining the latest version of all files: Version control ensures that everyone on your team is always working from the latest version of any file or document. This means you don’t have to worry about conflicting changes, duplication of work, or errors stemming from outdated versions.
2. Preserving a history of changes: With version control, you can see what changes were made to a file, who made them, and when. This is useful for understanding the evolution of a project and can be particularly valuable for auditing purposes.
3. Facilitating collaboration: Version control allows multiple people to work on the same file at the same time without overwriting each other’s changes. This makes it an excellent tool for facilitating collaboration and improving efficiency.
4. Preventing data loss: In the event of a mistake or an unexpected problem, version control allows you to easily restore previous versions of a file. This can be a lifesaver when it comes to preventing data loss.
5. Increasing transparency and accountability: By tracking who made which changes and when, version control increases transparency and accountability within your team.
6. Simplifying code management: Version control provides a clear history of changes by not only recording the changes made but also tagging them with timestamp information. This traceability makes it easier to understand the evolution of the code over time.
7. Identifying conflicts: Version control is instrumental in identifying and rectifying incompatible changes before the code reaches the customer environment. This proactive approach reduces errors and enhances the overall quality of the software product.

## Difference between GIT and GITHUB

Git is a distributed version control tool that can manage a development project's source code history, while GitHub is a cloud based platform built around the Git tool. Git is a tool a developer installs locally on their computer, while GitHub is an online service that stores code pushed to it from computers running the Git tool. The key difference between Git and GitHub is that Git is an open-source tool developers install locally to manage source code, while GitHub is an online service to which developers who use Git can connect and upload or download resources.

## list three other github alternatives

1. Radicle
2. Bitbucket
3. GitLab

## Explain the difference between git fetch and git pull

1. Git Fetch is Used to fetch all changes from the remote repository to the local repository without merging into the current working directory while Git Pull Brings the copy of all the changes from a remote repository and merges them into the current working directory.
2. Git Fetch Repository data is updated in the .git directory while Git Pull working directory is updated directly
3. Command for Git fetch is git fetch. while Command for Git Pull is git pull,
4. Git fetch basically imports the commits to local branches so as to keep up-to-date that what everybody is working on.Git Pull basically brings the local branch up-to-date with the remote copy that will also updates the other remote tracking branches.

## Explain in simple terms git rebase and the command for it

Rebasing is changing the base of your branch from one commit to another making it appear as if you created your branch from a different commit. Internally, Git accomplishes this by creating new commits and applying them to the specified base.

**Git rebase commands:**

1. git rebase - Performs the standard rebase
2. git rebase – interactive - This Performs the interactive rebase
3. git rebase -- d - The commit gets discarded from the final combined commit block during playback.
4. git rebase -- p - This leaves the commit alone, not modifying the content or message, and keeping it as an individual commit in the branches’ history.
5. git rebase -- x - This executes a command line shell script for each marked commit during playback.
6. git status - This Checks the rebase status.
7. git rebase -- continue - Continue with the changes that you made.
8. git rebase --skip - Skips the changes
9. The git add - add command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.
10. git commit -m  - "new commit for" Commits the changes.
11. Git Pull - Rebase Git pull is a command which is used to collect the changes from a remote repository and integrate them with the local branch. Git pull performs as a merge operator, but if you want to use it to rebase instead of merge, then you can utilize the Git pull rebase command.
12. git checkout - The git checkout command lets you navigate between the branches created by git branch.
13. The git push - this command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repository.
14. The git init command - creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
15. Git status - check the status, open the git bash, and run the status command on your desired directory.
16. Git clone - is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.
17. Git clean - is a convenience method for deleting untracked files in a repo's working directory.  
18. Git config command - is a convenience function that is used to set Git configuration values on a global or local project level.

## Explain in simple terms git cherry-pick and the command for it

git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. git cherry-pick can be useful for undoing changes.
To cherry-pick in Git, utilize the git log command to pinpoint the commit you want to cherry-pick. Then, cherry-pick the commit onto the target branch using the commit ID.
