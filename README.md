# assign3

Problem Definition

- create a branch from the master and made some changes 

- Commit code in a branch.

- Revert recently committed code

## git reset

`git reset` will undo changes up to the state of the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the second commit.git reset will undo changes up to the state of the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the second commit.

## git revert

`git revert` will undo changes up to the state before the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the commit that comes before the second commit – the first commit.

## When to Use git reset and git revert

You should use git reset when working on a local repository with changes yet to be pushed remotely. This is because running this command after pulling changes from the remote repo will alter the commit history of the project, leading to merge conflicts for everyone working on the project.

`git reset` is a good option when you realize that the changes being made to a particular local branch should be somewhere else. You can reset and move to the desired branch without losing your file changes.

`git revert` is a good option for reverting changes pushed to a remote repository. Since this command creates a new commit, you can safely get rid of your mistakes without rearranging the commit history for everyone else.