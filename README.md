# web_project
This repo was used for training purpose.  

 Introduction
This documentation report provides a comprehensive guide to Git and GitHub, two essential tools in modern software development. Git is a distributed version control system, and GitHub is a web-based platform built around Git, providing various collaboration and management features for software development projects.
<br><br>
Git<br>
Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It was created by Linus Torvalds in 2005 for the development of the Linux kernel. Git offers the following features:<br>
Version Control: Git tracks changes made to files, allowing developers to revert to previous versions or branch out for parallel development.<br>
Distributed: Each developer has a complete copy of the repository, enabling them to work independently without being connected to a network.<br>
Branching and Merging: Git allows for easy branching and merging, enabling parallel development and collaborative work.<br>
Lightweight: Git is designed to be fast and efficient, with most operations performed locally.<br>
Integrity: Git ensures the integrity of the source code through cryptographic hashing.<br><br>
Basic Git Commands<br>
git init: Initializes a new Git repository.<br>
git clone: Clones a repository into a new directory.<br>
git add: Adds file changes to the staging area.<br>
git commit: Records changes to the repository.<br>
git push: Pushes local changes to a remote repository.<br>
git pull: Fetches and merges changes from a remote repository.<br>
git branch: Lists, creates, or deletes branches.<br>
git merge: Merges changes from one branch to another.<br>
git checkout: Switches branches or restores working tree files.<br>
git status: Shows the status of the working directory.<br><br>
 Git Shortcuts and Tips<br>
Tab Completion: Use tab completion for Git commands and branch names.<br>
git log --oneline: View the commit history in a compact format.<br>
git diff: View the changes between the working directory, staging area, and the repository.
git reset HEAD <file>: Unstage changes from the staging area.
git stash: Temporarily save changes that are not ready to be committed.
git bisect: Find the commit that introduced a bug using binary search.
git blame: Identify the author of each line of code in a file.
git reflog: View the history of Git commands executed in the repository.
git clean -n: Preview the untracked files that will be removed by git clean -f.<br><br>
GitHub<br>
GitHub is a web-based platform built around Git, offering a range of features to facilitate collaboration, code review, and project management. It enhances Git with the following functionalities:<br>
Repository Hosting: GitHub hosts Git repositories, providing a central location for collaboration.<br>
Issue Tracking: GitHub allows users to track issues, assign tasks, and prioritize work within a project.<br>
Pull Requests: Developers can propose changes to a repository and request code reviews through pull requests.
<br>Collaboration Tools: GitHub provides collaboration tools such as wikis, project boards, and code review features.
<br>Integration and Automation: GitHub integrates with various third-party services and offers automation through GitHub Actions.
<br>Community and Social Features: GitHub fosters a strong developer community, allowing users to follow projects, contribute to open-source projects, and discover new codebases.<br><br>
Key GitHub Concepts<br>
<br>Repositories: GitHub hosts Git repositories, which can be public or private.
<br>Issues: Issues are used to track bugs, tasks, or feature requests within a repository.
<br>Pull Requests: Pull requests propose changes to a repository and facilitate code review and collaboration.<br>
Branches: Developers work on separate branches and merge changes back into the main branch through pull requests.<br>
Forks: Forking creates a personal copy of a repository, allowing users to freely <br>experiment with changes without affecting the original repository.
Stars: Users can "star" repositories to bookmark them or show appreciation.<br>
Watch: Users can "watch" repositories to receive notifications about new issues, pull requests, and other activity.<br>
Contributors: GitHub tracks contributors to a project, showcasing their contributions.<br><br>
Best Practices<br>
To effectively use Git and GitHub, it's important to follow best practices:<br>
Use Descriptive Commit Messages: Write clear and descriptive commit messages that explain the purpose of the changes.<br>
Frequent Commits: Make frequent, small commits rather than large, infrequent ones to keep the history clean and understandable.<br>
Branching Strategy: Adopt a branching strategy that fits your workflow, such as Gitflow, and stick to it.<br>
Code Reviews: Utilize pull requests for code reviews to maintain code quality and ensure collaboration.<br>
Documentation: Document your code, processes, and workflows to facilitate collaboration and onboarding.<br>
Use .gitignore: Utilize .gitignore files to exclude unnecessary files and directories from version control.<br>
Atomic Commits: Keep commits atomic, focusing on one logical change at a time.<br>
Rebase vs. Merge: Understand when to use rebase and when to use merge, depending on the context and the desired history

