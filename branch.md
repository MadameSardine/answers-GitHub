# A: A branch in git is a tool used to "travel back in time" and navigate through different scenarios.

Git tracks the changes made (and committed) to a project. You can see the history of these changes with the command: git hist.

By default, you are in a branch named "master".

If you want to "go back in time" to the point where you made a specific changes (commit), you can "branch" to this commit with the command: git checkout [commit_hash].

To go back to the master branch, type the command: git checkout master.

To try alternative versions of the project, you can create new branches with the command: git checkout -b [name_of_new_branch].