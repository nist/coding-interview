# Git

**1.What is git ?**
A Source Code Management (SCM) tool.

It allows to keep track of changes to a file, especially text files.
**2.Who created it ?**
Linus Torvalds
**3.What is GitHub ?**
It's a web application over git to manage repository and add a bunch of features, like project management, plugins and collaborative work.
**4.What is GitLab ?**
It's similar to GitHub, but with a more open approach and integrate CI and CD tools.
**5.What differ between GitHub and GitLab ?**
The core of GitLab is open source.
GitHub is close source, now own by Microsoft.
The set of features are different.
GitHub is more popular than GitLab. 
**6.What differ between a tag and a branch ?**
A tag is just a name given to a specific point in the timeline in the history of a repository.
A branch is a split in the timeline of the repository.
**7.How can a commit can be edited ?**

**8.How to delete a branch ?**
Locally : `git -d [branch name]`
Remote : `git push :[branch name]` 
**9.How to create a pull request ?**
It varies from project to project, but it genrally look like this:
1. Create a branch
2. Commit change to the branch
3. Push the branch to the repository
4. Send a pull request 
**10.What does the option --rebase does ?**
Apply the change history to the local repository.
**11.Where is the configuration ?**
`.git/config`
**12.What does git blame ?**
**13.What is a git hook ?**
A way to execute code when a action is done, like when code is pushed to the repository.
**14.What are GitHub actions ?**
Programmable tasks linked to a repository triggered by specific actions, like execute tests when new code is push in the repository.
**15.What is a fork ?**
A copy of a repository that can evolve separately from the original.