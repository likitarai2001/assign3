# assign3

Problem Definition

- create a branch from the master and made some changes 

- Commit code in a branch.

- Revert recently committed code

## git reset

`git reset` will undo changes up to the state of the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the second commit.git reset will undo changes up to the state of the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the second commit.

## git revert

`git revert` will undo changes up to the state before the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the commit that comes before the second commit – the first commit.