
Version control is a system that tracks changes to files over time, allowing multiple users to collaborate on a project. 
Record modifications to code and content over time, making it easy to revert to previous versions if necessary.
Allow collaboration where multiple people can work on the same project simultaneously without overwriting each other’s work.
Keep track of record as every change is recorded with a timestamp and author's identity, allowing for full accountability and documentation of changes.


Steps to set up 
1. Sign in to GitHub or create account
2.  To Create a New Repository Click the “New” button in the repository section.
   - Name your repository.
   - Choose whether the repo is public or private 


Importance of the README File

A README file is a section that allows users to comment or document there project and add instructions this encourages collaboration
It includes 
Project name and description
Installation instructions that hdirects ow to set up the project locally.
Explains how to use the project.
explains how others can contribute.

Public vs. Private Repositories
A public repository is one that is accessible to all people willing to view where as the private respiratory is only view by the creator /account’s user
A public repository encourages collaboration with other developers as one is able to acces the contents of the project whereas the private repository is only available to one user 
 

A commit is a snapshot of the project at a specific point in time. It records the changes made to files and adds them to the project's history.
steps
1. Clone a repository it locally using `git clone <repo URL>`.
2. Edit files or add new ones.
3. Use `git add <filename>` to add the files you want to include in the commit.
4. commit changes using `git commit -m "Your commit message"` to create a commit with a message describing the changes.
5. push changes using `git push` to send your changes to the GitHub repository.


Branching in Git

Branching allows users to work on different without affecting the main project. 
Isolating projects branch is independent, so changes won’t interfere with the main project until they are ready.
Feature development where one can create a branch for new features, test them, and merge them when they’re complete.


To create a branch:
1. Use `git checkout -b <branch-name>` to create and switch to a new branch.
2. Work on the branch independently.
3. When ready, merge it back into the main branch using a pull request or directly with `git merge`.

Branching facilitates parallel development and experimentation.

Pull Requests in GitHub Workflow

A pull request is a way to propose changes to a project. 
Process 
1. Creating a pull request After pushing changes to your branch, open a PR to request that your changes be merged into another branch 
2. Review the changes, discuss, and suggest modifications.
3. Merge this is done once modifications are  approved, the pull request is merged into the main branch, incorporating the new feature or fix.


Forking vs. Cloning

Forking is  creating a personal copy of another user’s repository. Changes made to your forked repo don’t affect the original until you submit a pull request  
Cloning  is copying a repository to your local machine. Changes made to a cloned repository are usually pushed back to the same repository you cloned.

Forking  is ideal for contributing to public projects without disturbing the original repo, while cloning is more about personal workspaces.

Issues and Project Boards

Issues are used to track bugs, tasks, or feature requests. They provide a space for discussion and can be linked to pull requests, commits, or project boards.

Project boards these organize tasks visually, often using Kanban-style boards, to improve project management.


Merge conflicts can arise when multiple developers modify the same file. Careful coordination and clear communication help minimize this.
Poorly documented repositories can be difficult for new contributors to understand.
-Unorganized commits, descriptive commits is key to ensuring a clear project history.

Best practices
Write clear commit messages
Create branches for features or fixes
-Use pull requests for code review
Regularly update the README and ensure clear documentation.
