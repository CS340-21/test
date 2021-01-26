The differences among github fork, git clone, and git branch:

Forking in github creates a copy of a repository. This enables users to experiment with the project
without affecting the original copy. Forks may be used to propose changes to a repository or to use 
another repository as a starting point. Forking a repository also allows the user to sync and fetch
updates from the original.

Git clone allows users to copy a repository onto their local machines. However, cloning a repository
does not let users submit pull requests to propose changes (instead, users must be added as collaborators).
A git clone is suitable when the copy does not need to be linked back to the original repository. 
Git clone is helpful for quick copies that bring the remote version of the repository local.

Git branch is used to view, create, and delete branches in a repository. Branches are different versions
of the primary project, which help users to edit things without modifying or messing up the entire
repository. Branches, which are designed to be short-lived and for quicker adjustments, may be merged back
to the master branch. In contrast, forking is meant for more permanent splits, when a user wants to
inherit things from a repository without merging back to it. Branches are often used to work on 
updates or to test functionality of a project.

I used GitHub Docs and GitHub community pages to find these differences.
