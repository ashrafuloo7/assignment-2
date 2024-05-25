full-stack-assignment-2-git
Git Branching, Merging, and Issue Handling Assignment
Instructions:
Part 1: Initial Setup

    Fork this Repository:

    Clone the Repository:
        Clone the forked repository to your local machine.

Part 2: Create a Feature Branch

Create a New Branch:

    Create and switch to a new branch named feature/added-learnings.

Create and Update a Readme:

    Create the learnings.md file and add a section titled "5 Things I have learned about Git and GitHub" with a brief description.

Commit the Changes:

    Add, commit, and push your changes to the remote repository.

git add learnings.md
git commit -m "Add Project Overview section to learnings.md"
git push origin feature/added-learnings

Part 3: Create an Issue and Add few more features

Create an Issue:

    On GitHub, create an issue titled "2 more things I have learnt".

Create another feature Branch:

    Create and switch to a new branch named feature/new-learnings.

Add the new features:

    In the  learnings.md file, add 2 more of your learnings.

Commit the feature branch:

    Add, commit, and push your changes to the remote repository.

git add learnings.md
git commit -m "added 2 more features in README"
git push origin feature/new-learnings

    Close the Issue:
        Go to GitHub and close the issue "2 more things I have learnt".

Part 4: Merge Branches

Merge the Feature Branch:

    Switch to the main branch and merge the feature/added-learnings branch.

git checkout main
git pull origin main
git merge feature/added-learnings

Merge the new feature Branch:

    Merge the feature/new-learnings branch into the main branch. If there are any conflicts, resolve them.

git merge feature/new-learnings

If there are conflicts:

    Open the conflicting files and resolve the conflicts manually.
    Mark the conflicts as resolved by adding the resolved files.

git add README.md
git commit -m "Resolve merge conflicts"

Push the Merged Changes:

    Push the merged changes to the remote repository.

git push origin main
