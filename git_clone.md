# A: git clone is used to clone a repository into a newly created directory.

In addition to that, git clone creates remote-tracking branches for each branch in the cloned repository.

After the clone, 'git fetch' will update will update all the remote-tracking branches.
A git pull will then merge the remote master branch into the current master branch.